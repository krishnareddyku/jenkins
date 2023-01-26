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
                     sh  'ansible-playbook /home/centos/jenkins/lab-ansible/sample.yml -e DATE=date -e ECHO=echo -e ROLE_NAME=frontend' 
                  }
                }

	}
}
