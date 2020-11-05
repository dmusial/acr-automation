pipeline {
    agent any

    parameters([
        string(name: 'imageName', defaultValue: '')
    ])

    stages {
        stage('Follows stable tagging') {
            steps {
                echo 'Checking tagging..${params.imageName}'
            }
        }
        stage('Based on standard image') {
            steps {
                echo 'Validating base image..'
            }
        }
        stage('Security compliant') {
            steps {
                echo 'Scanning....'
            }
        }
        stage('Promote to production') {
            steps {
                echo 'Promoting....'
            }
        }
    }
}