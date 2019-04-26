pipeline {
    agent any
    
    stages {
        stage('Compile Stage') {
		    steps{
		        withMaven(maven:'localMaven'){
	                    sh 'mvn clean compile'
				}
		    }
		}
    }
}