pipeline {
    agent {
        label '!windows'
    }

    environment {
        DATABASE = 'DB_NAME'
    }

    stages {
        stage('Database') {
            steps {
                echo "Database is ${DB_NAME}"
                sh 'printenv'
            }
        }
    }
}
