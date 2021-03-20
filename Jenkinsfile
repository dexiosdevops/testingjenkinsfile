pipeline {
    agent any
    parameters {
        string(name: 'STATEMENT', defaultValue: 'Class', description: 'What should I say?')
    }
    triggers {
        githubPush()
    }
    stages {
        stage('Build') { 
            steps {
                // 
                echo "Hello world"
                echo "${STATEMENT}"
                echo "nothing"
            }
        }
    }
}
