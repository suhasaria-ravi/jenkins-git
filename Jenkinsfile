pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                timeout(time: 1, unit: 'MINUTES') {
                    echo 'Deploying....'
                    sh 'for n in `seq 1 10`; do echo $n; sleep 1; done'
                }
            }
        }
    }
}

