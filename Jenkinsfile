pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello my friends'
      }
    }
    stage('email notification') {
      steps {
        mail(subject: 'testing blue ocean', to: 'lamkingshing18503@gmail.com', body: 'hello my friendy')
      }
    }
  }
}