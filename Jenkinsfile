pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Kalamoulah/jenkins_java_projetct.git'
            }
        }


          stage('Test') {
            steps {
                // Exemple : Exécution des tests
                sh 'mvn test'
            }
        }
        stage('Build') {
            steps {
                
                sh 'mvn clean install'
            }
        }

      
    }
}
