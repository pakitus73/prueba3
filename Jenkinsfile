pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t pakitus73/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        }
    }
}
