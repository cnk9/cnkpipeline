node {
      stage ('git clone'){
	  git credentialsId: 'github_root',url:'https://github.com/cnk9/cnkgit.git'
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
