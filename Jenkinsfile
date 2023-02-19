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
                echo "The value of the ENV parameter is: ${params.BRANCH}"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}