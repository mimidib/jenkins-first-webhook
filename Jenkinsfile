pipeline {
	agent any
	stages {
	    stage("build"){
	        steps{   
		    sh "echo Integrating Jenkins Pipeline with github webhook using jenkinsfile our webhook wont work"
		    sh "ls"
		    sh "echo configuration on pipeline works"
		    sh "python --version"
		    sh "python pipeline.py"
		}
	    }
	    stage("deployment"){
		steps {
		   sh "echo deployment stage has been completed"
		   sg "echo good bye"
		}
	    }
	}
}
