node {
      stage ('git clone'){
	  git credentialsId: 'https://github.com/cnk9/cnkpipeline.git'
	  }
	  stage('clean'){
	  sh 'mvn clean'
	  }
	  stage('compile'){
	  sh 'mvn compile'
	  }
	  stage('package'){
	  sh 'mvn package'
	  }
	  stage('deploy'){
	  sh 'mvn deploy'
	  }
	  }
