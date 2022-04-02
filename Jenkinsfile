pipeline {
         agent any
         stages {
                 stage('Build') {
                  steps {
                     echo 'staring build the app'
                  }
                 }
                 stage('Test') {
                  steps {
                        echo "App is tested"
                   }
                 }
             
                 stage('Deploy') {
                     steps {
                             input('Do you want to proceed?')  
                        }
                 }
      }
}