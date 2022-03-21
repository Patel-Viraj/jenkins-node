pipeline {
    agent any
    stages {
            stage('Stop node'){
                steps {
                    echo "hello"
                   // sh "pkill node"
                }
            }
            stage('Install packages'){
                 steps {
                     sh "npm i"
                 }
            }
            stage('Run project'){
                steps {
                    sh "node app.js &"
                }
            }
        // stage('git repo & clean') {
        //     steps {
        //         sh "rm -rf jenkins-node"
        //         sh "git clone https://github.com/Patel-Viraj/jenkins-node.git"
        //        // sh "mvn clean -f jenkins-node"
        //     }
        // }
        // stage('install') {
        //     steps {
        //        sh "npm install -f jenkins-node"
        //     }
        // }
    }
}
