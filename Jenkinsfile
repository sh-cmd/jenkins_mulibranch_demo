pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/sh-cmd/jenkins_mulibranch_demo.git'
            }
        }
        stage('print branch'){
            steps{
                sh 'sudo cat demo.txt'
            }
        }
    }
}
