pipeline {
    agent {
        node {
            label any
        }
  }

    options { skipDefaultCheckout() }
    stages {
        stage ('Build Stage') {
            agent none
            steps {
                script {
                    stage ('Checkout') {
                        echo 'This is a minimal pipeline for PayGo'
                        echo 'Checking out SCM'
                        checkout scm

                    }
			
                   stage ('build') {
                        echo 'this is the build stage'
                        echo 'YAY!!'
		   }
            }
        }

    }

}
}
