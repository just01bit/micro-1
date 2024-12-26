pipeline {
    agent {
        label 'built-in-node'
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World!!'
		sh 'vault status'
            }
        }
    }
}
