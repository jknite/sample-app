pipeline {
   agent any

   stages {
      stage('Build') {
         steps {
            sh 'mvn clean build'
         }
      }
      stage('Integration Test') {
         steps {
             echo 'do some integration tests'         
            
         }
      } 
      stage('Deploy') {
         steps {
            echo 'do deployment'
         }
      }  
            stage('Post Deploy validation') {
         steps {
            echo 'do validation'
         }
      }  
                  stage('Send notification') {
         steps {
            echo 'do notification'
         }
      }  
   }
}
