pipeline {
    agent any
    tools {
        maven '3.9.11'
    }
    stages {
        stage('Maven') { 
            steps {
                sh 'mvn -v' 
            }
        }
        
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}