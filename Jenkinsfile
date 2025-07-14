// Powered by Infostretch 

timestamps {

node ('Worker1_Build') { 

	stage ('Worker1_Build - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/main']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'gitHubCred', url: 'https://github.com/ayafor-code/javaWebApp.git']]]) 
	}
}
}
