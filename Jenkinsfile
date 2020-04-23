

//Declarative

pipeline{
agent {
	docker {image 'jenkins:3.9'}
}
stages{
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