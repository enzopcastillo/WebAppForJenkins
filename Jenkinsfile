pipeline {
    agent any
    tools {
        maven "maven-3.8.6"
    }
    stages {
        stage('Clean and Install') {
            steps {
               sh 'mvn clean install'
            }
        }
        stage('Package') {
            steps {
               sh 'mvn package'
            }
        } 
    }
}
