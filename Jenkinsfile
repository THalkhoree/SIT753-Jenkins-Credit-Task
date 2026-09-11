pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Task: Compile and package the application'
                echo 'Tool: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Task: Run unit tests and integration tests'
                echo 'Tools: JUnit and Selenium'
            }
        }
    }
}
