pipeline {
    agent {label 'java'}

    stages {
        stage('clone the') {
            steps {
                git branch: 'main', url: 'https://github.com/gowdas-pruthvi/springboot-app-b17.git'
            }
        }
        stage('build') {
             steps {
                sh 'mvn clean package'
            }
        }
    }
}
