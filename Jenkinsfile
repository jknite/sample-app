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
   }
}
