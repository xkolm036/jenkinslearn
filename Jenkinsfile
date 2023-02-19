 pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Buildingwww..'
            }
        }
        stage('Test') {
            steps {
                choice(name: 'BRANCH', choices: ['Master', 'Dev'])
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
