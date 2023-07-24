pipeline {
    agent any 
    stages {
        stage ('Get Env Variables') {
            sh 'printenv'
        }
        stage('Git Version') { 
            sh 'git version'
        }
        stage('Docker Version') { 
            sh 'docker -v'
        }
        stage('Maven version') { 
            sh 'mvn version'
        }
    }
}
