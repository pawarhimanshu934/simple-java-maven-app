pipeline {
    agent any
    tools {
        maven 'Maven 3.9.9'  // This uses the Maven installation you configured in Jenkins
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
