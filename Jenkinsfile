pipeline {
	agent any
	stages {
		stage('helo') {
		  steps {
			echo "haloo world"
		  }
		}
                stage('sample') {
                  steps {
                     sh  'ansible-playbook sample.yml -e DATE=date -e ECHO=echo -e ROLE_NAME=frontend' 
                  }
                }

	}
}
