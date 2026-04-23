@Library('shared-lib') _

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                buildApp()
            }
        }

        stage('Test') {
            steps {
                testApp()
            }
        }

        stage('Scan') {
            steps {
                scanApp()
            }
        }

        stage('Deploy') {
            steps {
                deployApp()
            }
        }
    }
}
