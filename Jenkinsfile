pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                withMaven {
      sh "mvn clean install"
    }
                echo 'Building..'
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
