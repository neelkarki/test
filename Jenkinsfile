pipeline {
 agent any
  stages {
    stage("Code Checkout from GitLab") {
     steps {
         git changelog: false, credentialsId: 'c4eeed53-8b2b-4106-9623-453d4150e150', poll: false, url: 'https://github.com/neelkarki/test.git'
     }
      }
     }
}
