pipeline {
    agent any

    stages {
        stage('Checkout') {
          steps {
          dir('HelloWorlds') {
          git url: 'https://github.com/lukavucko/hello_world_gradle'
    }
          }
        }
        stage('Build') {
            steps {
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
