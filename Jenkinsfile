pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello build'
            }
        }
      stage('Test') {
            steps {
                echo 'Hello Test'
            }
        }
      stage('Deploy') {
            steps {
                echo 'Hello deploy'
            }
        }
    }
  post{
    always{
     emailext body: 'hello all', subject: 'scmpipeline', to: 'simranferoz31@gmail.com'
    }
    
  }
  
}
