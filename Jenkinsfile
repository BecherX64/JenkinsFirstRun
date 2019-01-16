pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Stage 1 - Start' 
                echo 'Current folder:'
                sh 'pwd'
            }
        }
        stage('Stage 2') {
            steps {
                echo 'Stage 2 - Start' 
                echo 'Listing $HOME Folder'
                sh 'ls -l $HOME'
            }
        }
    }
}
