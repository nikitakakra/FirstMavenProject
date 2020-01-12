node{
    stage('SCM Checkout'){
	   git 'https://github.com/nikitakakra/FirstMavenProject/'
	}
	stage('compile package'){
	  // def mvnHome = tool name: 'Maven 3.5.0', type: 'maven'
	   sh 'mvn package'
	}
}
