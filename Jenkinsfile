pipeline {
  agent {
    docker {
      image 'shazchaudhry/docker-centos:latest'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'terraform --version'
        sh 'ansible --version'
        sh 'mvn --version'
        sh 'java -version'
        sh 'javac -version'
        sh 'git --version'
      }
    }
  }
}