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

	stage('Second'){
	    steps{
		sh '''
		   echo "Hey this is second stage latest one"
		'''
	   }
	}


	stage('Third'){
	    steps{
		sh '''
		  echo "Rey this is the third one"
		  echo "jumbare ajumbare"
		'''
	  }
	}
     }
 }
