pipeline {
         agent any
         stages {
                 stage('Build') {
                  steps {
                     echo 'staring build the app'
                     sh 'npm i'
                  }
                 }
                 stage('build') {
                  steps {
                        echo "App is building"
                        sh 'npm build-dev'
                   }
                 }
             
      }
}
