pipeline
 {
 	agent any
 	stages
 	 {
 	  stage('Build')
 	   {
 	    bat 'mvn clean install'
 	   }
 	   stage('Deploy to cloudhub')
 	   {
 	    bat 'mvn package deploy -DmuleDeploy'
 	   }
 	 }
 }