pipeline {
  environment {
    dockerimagename = "bravinwasike/react-app"
    dockerImage = ""
  }
  agent any

  stages {

    stage('Checkout Source') {
      steps {
        git url: 'https://github.com/Bravinsimiyu/jenkins-kubernetes-deployment.git', branch: 'main'
        sh "ls -l"
      }
    }
  }

}
