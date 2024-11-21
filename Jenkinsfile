pipeline{
 agent any

    stages{
         stage('Clone Repository') {
            steps {
                git 'https://github.com/ShashankSrivatsaRao/Jenkins_Test.git'
            }
        }
        stage('Compile') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
