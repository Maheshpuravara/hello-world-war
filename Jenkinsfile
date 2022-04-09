pipeline {
    agent none 
    stages {
        stage ('checkout') {
agent { label 'java' }
            steps {
                sh 'git clone https://github.com/Maheshpuravara/hello-world-war.git'
            }
        }

stage('build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
