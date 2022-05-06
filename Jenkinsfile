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
	stage('Finale'){
		steps {
		  sh '''
			echo "Rey in feature rey"
		   '''
	  }
	}
=======

	stage('Third'){
	    steps{
		sh '''
		  echo "Rey this is the third one"
		  echo "jumbare ajumbare"
		'''
	  }
	}

>>>>>>> master
     }
 }
