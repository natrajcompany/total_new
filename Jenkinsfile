pipeline{
    agent {
        docker {
		images 'ubuntu:latest'
		args '-u root'
	}
   }

    stages{
	stage('First'){
           steps{
	     sh '''
		echo "hello-world"
		'''
	   }
	}
     }
 }
