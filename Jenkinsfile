node{
    stage('SCM Checkout'){
	   git 'https://github.com/nikitakakra/FirstMavenProject/'
	}
	stage('compile package'){
	  bat 'mvn package'
	}
}
