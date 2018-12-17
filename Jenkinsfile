pipeline {
    agent none
    options { skipDefaultCheckout() }
    stages {
		stage ('Checkout') {
			agent {
				label mastrer
		    }
			steps {
				echo 'This is a minimal pipeline for HCP Vacancies'
				echo 'Checking out SCM'
				checkout scm
			}
		}
		stage('Build') {
			agent {
				label any
		    }
			steps {
				echo 'Building..'
			        echo 'yay!!!'
			}
		}
  }
}
