pipeline {
    agent any 
    stages {
        stage('create folder') { 
            steps {
                sh 'sudo mkdir /tmp/testing_pipeline' 
            }
        }
        stage('date') { 
            steps {
                sh 'sudo date' 
            }
        }
        stage('calender') { 
            steps {
                sh 'sudo cal'
            }
        }
    }
}
