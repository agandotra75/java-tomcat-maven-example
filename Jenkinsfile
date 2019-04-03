pipeline {
    agent any
    stages {
stage  ('initialization') {
	    steps {
	        echo "path = ${path}"
	        echo "M2_HOME = ${M2_HOME}"
		    }
		}    
        stage  ('Build') {
	    steps {
		echo "Hello World"
            }        
		}      
      stage  ('Deploy') {
	    steps {
		echo "Delpoy and Artifact"
            }        
		}      

    
    }	

  }
	
