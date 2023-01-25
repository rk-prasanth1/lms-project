pipeline{
	agent any

	stages {
	    stage ('build') {
	        steps {
	            sh 'cd webapp && install npm'
	            sh 'cd webapp && npm run build'
	        }
	    }
	}
}
