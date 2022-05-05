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
		'''
	  }
	}

	stage('Final'){
	  steps{
	     git init
	     git config user.name "natrajsai8"
	     git config user.email "natrajsai7@gmail.com"
	     git status
	     git checkout -b rc
	   }
	}
     }
 }
