pipeline {

    agent any

    stages {

        stage("Git Checkout"){
            steps {
                git branch: 'main', url: 'https://github.com/vaishnavbalodhi/java-app.git'
            }
        }

        stage("Unit Testing"){
            steps {
                sh 'mvn test'
            }
        }
    }
}
