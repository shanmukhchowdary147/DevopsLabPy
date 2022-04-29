pipeline {
    agent any
    stages{
        stage ('Build'){
            steps{
                echo 'Building...'
                bat 'python ll.java'
            }
        }
        stage ('Test'){
            steps{
                echo 'Using maven'
            }
        }
    }
}