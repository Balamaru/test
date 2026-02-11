pipeline {
  agent {
    kubernetes {
      label 'kubeagent'
    }
  }

  stages {
    stage('Test') {
      steps {
        sh 'echo "ini dari shell jenkins"'
      }
    }
  }
}
