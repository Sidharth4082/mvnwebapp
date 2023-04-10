pipeline {
    agent any
	tools {
	  maven 'Minstall'      
	}
	stages {
	  stage('Example') {
	    steps {
		  sh 'mvn clean install'
	    }
	}
}
}
