pipeline {
         agent any
         stages {
                 stage('Build') {
                  steps {
                     echo 'staring build the app'
                     npm i
                  }
                 }
                 stage('build') {
                  steps {
                        echo "App is building"
                        npm build-dev
                   }
                 }
             
                 stage('Deploy') {
                     steps {
                             input('Do you want to proceed?')  
                        }
                 }
      }
}
