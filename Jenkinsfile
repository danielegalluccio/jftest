pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                /dev/ws/Jiraton/Tickets_in_Column.sh
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.... ${select-env}'
                echo "value ${str}"
            }
        }
    }
}
