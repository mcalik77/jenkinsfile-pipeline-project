pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }
       stage('trigger') {
            steps {
                echo 'This one poll the code from SCM'
                
            }
        }
       stage('Last change') {
            steps {
                echo 'Last change'
                
            }
        }
       
    }
}
