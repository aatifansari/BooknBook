pipeline{
	agent any
	stages{
	stage('One'){
	             steps{
	                echo 'BooknBook Pipeline'
	             }
	
	}
	stage('Two'){
	             steps{
	                echo input('Do you want to proceed?')
	             }
	
	}
	stage('Three'){
	               when{
	                    not{
	                         branch "master"
	                    }
	               }
	               steps{
	                    echo "Hello"
	               }
	}
	stage('Four'){
	             
            steps {
                echo 'Building..'
            }
	

	}

	
}
}
