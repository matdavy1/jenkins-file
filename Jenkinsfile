pipeline {
    agent any
    parameters {
        string(name: 'param1', defaultValue: '', description: 'Greeting message')
        string(name: 'param2', defaultValue: '', description: '2nd parameter')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Hello world!'
                echo "message: ${params.param1}"
                echo "param2: ${params.param2}"
            }
        }
    }
}
