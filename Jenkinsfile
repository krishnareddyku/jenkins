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
	

	post {
	  always {
	    echo "send mail"
	  }
	}

          changed {
            echo "changed from last to present"
          }
        }
}
