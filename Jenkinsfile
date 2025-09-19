pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Building the code using Maven...'
                echo 'Tool used: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Running unit and integration tests...'
                echo 'Tools used: JUnit for unit tests, TestNG for integration tests'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Performing static code analysis...'
                echo 'Tool used: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Performing security scan...'
                echo 'Tool used: OWASP Dependency-Check or Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploying application to staging environment (e.g., AWS EC2)...'
                echo 'Tool used: SCP or AWS CLI or Ansible'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Running integration tests on staging...'
                echo 'Tool used: Postman / Newman or Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploying application to production environment (e.g., AWS EC2)...'
                echo 'Tool used: AWS CLI or Jenkins SSH plugin or Ansible'
            }
        }
    }
}
