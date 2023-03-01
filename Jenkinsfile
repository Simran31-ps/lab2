pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello builllllld'
            }
        }
      stage('Test') {
            steps {
                echo 'Helllllllllllo Test'
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
