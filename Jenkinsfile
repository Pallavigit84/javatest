pipeline {
    agent any

    tools { 
      maven 'maven'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('code quality') {
            steps {
                echo 'code quality'
            }
        }    
        stage('Depoloy to Dev') {
            steps {
                echo 'depoly to dev'
            }
        }
        stage('Depoly to test') {
            steps {
                echo 'Deploy to test'
            }
        }    
        stage('Depoly to UAT') {
            steps {
                echo 'Deploy to UAT'
            }
        }    
         stage('Depoly to Pre_prod') {
            steps {
                echo 'Deploy to Pre_prod'
            }
        }   
         stage('Depoly to prod') {
            steps {
                echo 'Deploy to prod'
            }
        }   
    }
}
