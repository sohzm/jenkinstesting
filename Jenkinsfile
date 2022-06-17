pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh "./build.sh"
            }
        }
        stage('Run') {
            steps {
                sh "./a.out"
            }
        }
    }
}

