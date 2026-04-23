@Library('shared-lib') _

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build()
            }
        }

        stage('Test') {
            steps {
                test()
            }
        }

        stage('Scan') {
            steps {
                scan()
            }
        }

        stage('Deploy') {
            steps {
                deploy()
            }
        }
    }
}
