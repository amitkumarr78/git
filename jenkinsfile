pipeline {
  agent any

  stages {
    stage('Test') {
      steps {
        echo "Webhook working"
      }
    }
    stage('Build Docker Image') {
      steps {
        sh 'docker build -t myapp .'
      }
    }
    stage('Deploy') {
  steps {
    sh '''
    docker stop mycontainer || true
    docker rm mycontainer || true
    docker run -d -p 8081:80 --name mycontainer myapp
    '''
  }
}
  }
}
