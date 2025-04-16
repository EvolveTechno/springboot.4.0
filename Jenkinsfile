node('master'){
	   
	   stage('Git checkout'){
	                  git 'https://github.com/EvolveTechno/springboot.4.0.git'
	              }


	   stage('Build approval') 
        {
                          input "Build the app?"
        }
	 
	   stage('Build'){
	             sh 'mvn clean install'
	         }
	         	   stage('Deployment approval') 
        {
                          input "Deploy the app?"
        }
	            
	}
