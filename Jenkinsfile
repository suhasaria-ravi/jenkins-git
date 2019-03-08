pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                timeout(time: 1, unit: 'MINUTES') {
                    sh 'for n in `seq 1 5`; do echo $n; sleep 1; done'
                }
            }
        }
    }
}

