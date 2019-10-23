// Powered by Infostretch 

timestamps {

node () {

	stage ('testing - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '05869e8d-b984-4437-8d3b-faffd9b74c93', url: 'https://github.com/shaikkhaja5628/New1.git']]]) 
	}
	stage ('testing - Build') {
 			// Shell build step
sh """ 
cd /home/instance/
rm -rf * 
 """ 
	}
}
}