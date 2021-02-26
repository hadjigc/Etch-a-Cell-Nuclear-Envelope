pipeline {
    agent { node { label 'master' } }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		env
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
