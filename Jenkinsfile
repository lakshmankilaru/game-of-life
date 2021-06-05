pipeline {
    agent any
    stages {
        stage('git') {
            steps{
                git 'https://github.com/lakshmankilaru/game-of-life.git'
            }
        }
        stage('maven build stage') {
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
