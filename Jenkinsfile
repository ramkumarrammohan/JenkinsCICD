#!groovy

node {

    try {
        stage('Checkout') {
            checkout scm
            echo 'Checking Out'
        }

        stage('Build') {
            echo 'Building'
        }
        
    } catch (err) {
        echo 'Error occured!!!'
        throw err
    }
}


