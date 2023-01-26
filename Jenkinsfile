pipeline {
    agent {
       label 'kk'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
	stage('test-ansible') {
	    steps {
		sh 'ansible-playbook /home/centos/Roboshop-ansible/lab-ansible/sample.yml -e DATE=date -e ECHO=echo -e ROLE_NAME=frontend'
        }
}

