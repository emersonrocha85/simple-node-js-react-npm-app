pipeline {
    agent any 
	
	tools {nodejs "node"}
    
	stages {
        stage('Build') {
            steps {
                git 'https://github.com/emersonrocha85/simple-node-js-react-npm-app'
				bat 'npm install'
            }
        }

    }
  }