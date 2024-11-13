pipeline{
	agent any

	stages{
	stage("Print Jenkins Stage"){
		steps {
			sh 'echo "Jenkins changes ran Successfully!"'
		}
	}
	 stage("Added new Stage"){
                steps {
                        sh 'echo "Pushed polling changes!"'
                }
        }

	}
}
