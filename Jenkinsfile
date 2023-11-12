pipeline {
    agent any
    triggers {
        cron('H/60 * * * *')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Testing cron... '
            }
        }
    }
}
