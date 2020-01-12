node{
    stage('SCM Checkout'){
	   git 'https://github.com/nikitakakra/FirstMavenProject/'
	}
	stage('compile package'){
	   sh 'mvn package'
	}
}
