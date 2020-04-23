

//Declarative

pipeline{
agent {docker {image 'jenkins:3.6.3'}
args '-u root:root'}
stages{

	stage('Permision'){
		steps{
			sh 'chmod 775*'
		}

	}
	stage('Build'){
		steps{
			echo "Build";
		}
	}
	stage('Test'){
		steps{
			echo "Test";
		}


	}

	stage('Integration Test'){
		steps{
			echo "Integration Test2";
		}
	}
}
post{

	always{
		echo " i run always"
	}
	success{
		echo " i run when sucess"
	}
	failure{
		echo " i run when failure"
	}
}

}