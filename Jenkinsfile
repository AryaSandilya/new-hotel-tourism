pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                git branch: 'main', url: 'https://github.com/AryaSandilya/new-hotel-tourism.git'
                
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

    }
}