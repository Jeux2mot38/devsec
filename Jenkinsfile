pipeline {
    agent none
    stages {
        stage("Build & Analyse avec SonarQube") { 
            agent any
            steps { 
                script {
                    sh 'mvn clean package sonar:sonar'
                }
            }
        }
    }
}
