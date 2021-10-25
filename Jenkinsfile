pipeline {
    agent any
    stages {
        stage("Run") {
            steps {
                sh "python main.py"
                echo "Running done" 
            }  
        } 
        stage("Unit test"){
            steps {
                sh "python test.py"
                echo "Testing done"
            }
        }
        stage("Integration Testing"){
            steps {
                echo "Integration Testing done"
            }
        }
        // stage("Something Else"){
        //     steps {
        //         echo "Something Else done"
        //     }
        // }
    }
}