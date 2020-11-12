pipeline {
    agent any
    tools{
        go 'go'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git 'https://github.com/Naveen486/Jenkins.git'
                sh 'go version'
                sh 'go build Hello.go'
                sh './Hello'
            }
        }
    }
}
