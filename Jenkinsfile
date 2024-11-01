// First Pipeline 

pipeline {
    agent any 
    stages  {
        stage('Build') {
            steps {
                echo "Building the application"
               // sh "mvn package -Dskip.tests=true"
            }
        }
        stage('Sonar') {
            steps {
                echo "Executing Sonar"
                //sh "mvn sonar:sonar"
            }
        }
        stage('DockerBuild') {
            steps {
                echo "Builing Docker Image"
                //sh "docker build -t xyz ."
            }
        }
    }
}
