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


<<<<<<< HEAD
	stage('Third'){
	    steps{
		sh '''
		  echo "Rey this is the third one"
		'''
	  }
	}

        stage('Four'){
	   steps{
	     sh '''
		apt-get update
		apt-get install jenkins -y
		echo "Yes im forking"
		'''
	  }
	}
=======
>>>>>>> 2f852e6c4f289d56e6b5a5f6d73b89ab893f2e7d
     }
 }
