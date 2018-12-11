node{
	stage('Checkout'){
		checkoutscm
	}
	
	stage('Build'){
		 sh 'mvnw clean install -q'
	}
}
