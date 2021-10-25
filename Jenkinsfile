pipeline {
    agent any
    stages {
        stage("Run") {
            sh "python main.py"
            echo "Running done"   
        } 
        stage("Unit test"){
            sh "python test.py"
            echo "Testing done"
        }
    }
}