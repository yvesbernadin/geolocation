pipeline {
    agent any
    tools {
        maven 'M2_HOME'

    }
    stages {
        stage('maven build jenkins'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}