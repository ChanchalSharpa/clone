pipeline{
		
		agent{
			
			label "built-in"
			customWorkspace "/mnt/papa/"
		}
		
		stages{
			
			stage("stage-01"){
				steps{
				sh "docker run -itd httpd"
				}
			}
		}







}
