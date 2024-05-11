@Library('roboshop') _

pipeline {
    agent any

    stages {

        stage('Compile Test') {
            steps {
                echo 'Compiling The Code.'
                script {
                    demo.info 'Starting'
                    demo.warning 'Nothing to do!'
                }
            }
        }

        stage('Test') {
            steps {
                echo 'Test The Code.'

            }
        }
        stage('Code Quality') {
            steps {
                echo 'Code Quality'
            }
        }
        stage('Code Security') {
            steps {
                echo 'Code Security'
            }
        }


    }
