node{
    stage('SCM Checkout'){
	   git 'https://github.com/nikitakakra/FirstMavenProject/'
	}
	stage('compile package'){
	   def mvnHome = tool name: 'maven-3', type: 'maven'
	   sh "${mvnHome}/bin/mvn package"
	}
}
