pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello_World"'
      }
    }
  }
  environment {
    npm_config_cache = 'npm_cache'
  }
}
