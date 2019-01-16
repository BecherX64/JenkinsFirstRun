pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Stage 1 - Start' 
                echo $HOME
            }
        }
        stage('Stage 2') {
            steps {
                echo 'Stage 2 - Start' 
                echo 'Listing $HOME Folder'
                ls -l $HOME
            }
        }
    }
}
