// test
//build 1
pipeline{
	agent any 
	stages{
		stage('git-clone'){
			steps{
           checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/DTM-Solutions/Etech-lab.git']]])
			}
		}
	}	
	
}
