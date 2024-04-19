pipeline {
   //agent none
	agent any
    		stages {
        		stage('Run Tests') {
                	stage('Test On Master') {
                   	 	agent {
                        		label "mock"
                    		}
                   		 steps {
			    		sleep 4
					echo "Task2 on Parallel"
				}
                	}
            	}
        }
}

