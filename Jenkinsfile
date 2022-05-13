pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello from git'
                bat ("python hello.py")
            }
        }
    }
}
