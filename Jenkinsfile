pipeline {
 // adding an agent is compulsory
 agent any
	stages {
	stage('checkout') {
	  steps {
	   git 'https://github.com/mohanna-t/my-test.git'
	  }
	 }
	 stage('build') {
	  steps {
	   bat "hello2.bat"
	  }
	 }
	}
}