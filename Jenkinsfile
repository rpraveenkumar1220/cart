pipeline {
    agent { label 'workstation'}
    stages {
        stage('Build') {
         steps { sh 'npm install'    }
         }
        stage('Unit Test'){
         steps { echo "Unit testing"  }
         }
        stage('Code Analysis'){
        steps { echo "Code Analysis"  }
        }
        stage('Security Scans'){
        steps { echo "Security Scans" }
        }
        stage('Publish Artifacts'){
        steps { echo "Publish Artifacts" }
        }
            }
           }
