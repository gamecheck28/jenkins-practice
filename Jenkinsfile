pipeline {
    agent any
    triggers {
        cron('H/1 * * * *')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World New'
            }
        }
    }
}
