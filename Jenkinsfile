pipeline {
    agent any
    parameters {
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
		string(name: 'BIOGRAPHY', defaultValue: 'Mr Jenkins', description: 'BIOGRAPHY')
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
                echo "Biography: ${params.BIOGRAPHY}"
            }
        }
    }
}