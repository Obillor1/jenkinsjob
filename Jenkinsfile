pipeline {
    agent any 
    stages {
        stage('Git Version') { 
            sh 'git version'
        }
        stage('Docker Version') { 
            sh 'docker -version
        }
        stage('Maven version') { 
            sh 'mvn -v'
        }
    }
}
