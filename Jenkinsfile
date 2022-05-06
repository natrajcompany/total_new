pipeline{
    agent {
        docker {
		image 'ubuntu:latest'
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

	stage('Second'){
	    steps{
		sh '''
		   echo "Hey this is second stage latest one"
		'''
	   }
	}


     }
 }
