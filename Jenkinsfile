pipeline {
    agent any 
    stages {
        stage('Git Version') { 
            steps 'git version'
        }
        stage('Docker Version') { 
            steps 'docker -v'
        }
        stage('Maven version') { 
            steps 'mvn version'
        }
    }
}
