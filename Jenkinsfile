pipeline{
	agent any

	stages {
	    stage ('build') {
	        steps {
	            sh 'cd webapp && npm install'
	            sh 'cd webapp && npm run build'
	        }
	    }
	}
}
