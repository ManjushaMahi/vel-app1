pipeline { 
	agent {

		label {

			label "built-in"
			customWorkspace "/mnt/test"
		
		}
        }
	stages {
		stage ('óne') {
			
			steps {
				sh " sudo yum install httpd -y"
				sh "sudo cp index.html /var/www/html/"
				sh " sudo servie httpd start"
				sh " sudo chmod -R 777 /var/www/html/index.html"
			}
		

			
		}
	}
}
