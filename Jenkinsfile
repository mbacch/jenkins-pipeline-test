pipeline {
    agent { label 'master' }
    stages {
        stage('analysis1') {
            steps {
                echo "Hello World!"
                sh 'echo "Hello again!" > hello.txt'
                sh 'pwd'
                sh 'ls'
            } //steps
        } // stage analysis 1
        stage('analysis2') {
            steps {
                echo "Hello analysis stage 2!"
            } //steps           
        } //stage
    } //stages
} //pipeline
