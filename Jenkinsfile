pipeline {
    agent any

    stages {
        stage('Commit') {
            steps {
                echo 'commit sucesss'
            }
        }
            stage('push') {
            steps {
                echo 'code merged sucess'
            }
        
        }
        stage('Merge') {
            steps {
                echo 'Test runeed sucess'
            }
        }
        stage('Test') {
            steps {
                echo 'Test to prod'
            }
        }
          stage('Release') {
            steps {
                echo 'release to prod'
            }
        }
    }
}
