pipeline {
    agent any
    stages {
        stage ('Build'){
            steps {
              echo 'Running build automatio'
              sh './gradlew build --no-daemon'
              archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
