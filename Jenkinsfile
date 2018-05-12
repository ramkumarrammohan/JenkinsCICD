#!groovy

node {

    try {
        stage('Checkout') {
            checkout scm
            sh 'ls -l'
            echo 'Checking Out'
        }

        stage('Build') {
            sh 'ls -l'
            sh 'pwd'
            echo 'Building'
        }
        
    } catch (err) {
        echo 'Error occured!!!'
        throw err
    }
}


