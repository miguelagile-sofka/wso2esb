node{
	stage('Checkout'){
		checkout scm
	}
	
	stage('Compile'){
		 sh 'mvn clean install -q'
	}
}
