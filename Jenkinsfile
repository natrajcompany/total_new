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
		   echo "Hey this is second stage"
		'''
	   }
	}


	stage('Third'){
	   when {
		  branch 'feature'
		}
	    steps{
		sh '''
		  echo "Rey this is the third one"
		'''
	  }
	}

        stage('Four'){
	   when {
		  branch 'ttt'
		}
	   steps{
	     sh '''
		apt-get update
		apt-get install git -y
		git --version
		echo "Yes im forking"
		'''
	  }
	}
	stage('Five'){
	     steps{
		sh '''
		echi "stages five 
		from nat_fork branch for testng  have added this stsep"
		'''
	   }
	}
     }
 }
