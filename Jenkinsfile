pipeline {
    agent any
    tools {
        maven 'maven_3.9.11'
        jdk 'jdk_21'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}