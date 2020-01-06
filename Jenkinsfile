pipeline {
    agent any
    
    // Tools are installed in the machine and configured in Global Configuration Tools
    tools {
        jdk 'openjdk'
        gradle 'gradle'
    }
    stages {
        stage('Build') {
            steps {
                sh './gradlew build'
            }
        }
    }
}
