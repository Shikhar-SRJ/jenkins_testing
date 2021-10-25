pipeline {
    agent any
    stages {
        stage("Run") {
            sh "python3 main.py"
            echo "Running done"   
        } 
        stage("Unit test"){
            sh "python3 test.py"
            echo "Testing done"
        }
    }
}