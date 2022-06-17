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
                echo 'Running..'
                sh "./a.out"
            }
        }
    }
}

