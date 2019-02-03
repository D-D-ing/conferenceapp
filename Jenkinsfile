node{
	stage('prepare'){
		checkout scm
		
		sh("git submodule update --recursive")
		sh("git commit -m Jenkins triggers monorepo to update")
		sh("git push")
	}
	stage('build'){
		//do docker stuff
	}
	stage('test'){
		//do docker stuff again
	}
	stage('deploy'){
		// restart all the images, make the frontends accessible
	}
}