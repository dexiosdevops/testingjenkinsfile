pipeline {
    agent any
    triggers {
        pollSCM('') //Empty quotes tells it to build on a push
    }
    parameters {
        string(name: 'STATEMENT', defaultValue: 'Class', description: 'What should I say?')
    }

    stages {
        stage('Build') { 
            steps {
                // 
                echo "Hello world"
                echo "${STATEMENT}"
                echo "nothing"
                echo "adding new file"
            }
        }
    }
}
