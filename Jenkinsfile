pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build - The code is compiled and packaged using a build automation tool.'
                echo 'Tool Used: Maven' // As suggested in the task [cite: 30]
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests - Unit tests are run to verify individual code functions, and integration tests ensure components work together.' // [cite: 31, 33]
                echo 'Tools Used: JUnit for unit tests, TestNG for integration tests.'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis - A static code analysis tool scans the code to ensure it meets industry standards.' // [cite: 34]
                echo 'Tool Used: SonarQube' // A selected tool as required [cite: 35]
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan - The code is scanned to identify potential security vulnerabilities.' // [cite: 36]
                echo 'Tool Used: OWASP ZAP' // A selected tool as required [cite: 37]
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging - The application is deployed to a staging server for further testing.' // [cite: 38]
                echo 'Tool Used: Ansible for deploying to an AWS EC2 instance.'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging - Integration tests are run in a production-like environment to ensure the application functions correctly.' // [cite: 39]
                echo 'Tool Used: Selenium'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production - The application is deployed to the production server for end-users.' // [cite: 40]
                echo 'Tool Used: Ansible for deploying to an AWS EC2 instance.'
            }
        }
    }
}
