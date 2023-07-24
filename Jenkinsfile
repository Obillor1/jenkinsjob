pipeline {
    agent any 
    stages {
        stage ('Get Env Variables') {
            steps {
            sh 'printenv'
            }
        }
        stage('Git Version') { 
            steps {
            sh 'git version'
            }
        }
        stage('Docker Version') {
            steps {
            sh 'docker -v'
            }
        }
        stage('Maven version') {
            steps {
            sh 'mvn -v'
            }
        }
    }
}
