pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Gradle'
                withGradle() {
                    sh 'gradlew -v'
                }
                
            }
        }
    }
}
