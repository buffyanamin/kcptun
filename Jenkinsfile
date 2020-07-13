pipeline {
  agent any
  stages {
    stage('build_client') {
      steps {
        sh 'go build -ldflags -X main.VERSION=1.0 -s -w           github.com/xtaci/kcptun/server'
      }
    }

  }
}