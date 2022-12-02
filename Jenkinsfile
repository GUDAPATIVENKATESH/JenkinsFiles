pipeline{
    agent {label ''}
    stages {
        stage('clone') {
            steps {
                git url: 'https://github.com/GUDAPATIVENKATESH/Docker.git' ,
                branch : 'main' 
            }
        }
        stage('build') {
            steps {
                sh 'docker image build -t joip:1.0 .'
            }
        }
    }
}