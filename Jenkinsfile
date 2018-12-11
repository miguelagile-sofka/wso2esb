node{
	stage('Checkout'){
		checkout scm
	}
	
	stage('Compile'){
		 sh './mvnw clean install -q'
	}
}
