pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh build.sh
            }
        }
        stage('Run') {
            steps {
                ./a.out
            }
        }
    }
}

