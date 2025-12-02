pipeline {
    agent any
    stages {
        stage('Build Java') {
            steps {
                echo 'Compiling Java...'
                // This command compiles the code
                sh 'javac App.java' 
            }
        }
        stage('Test Java') {
            steps {
                echo 'Running Java Application...'
                // This command runs the code
                sh 'java App'
            }
        }
    }
}
