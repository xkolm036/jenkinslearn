 pipeline {
    agent any
    parameters{
        choice(name: 'BRANCH', choices: ['Master', 'Dev'], description: 'Choose branch')

    }
    stages {
        stage('Build') {
            steps {
                echo 'Buildingwww..'
            }
        }
        stage('Test') {
            steps {  
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}