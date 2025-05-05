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
				sh "yum install httpd -y"
				sh "cp index.html /var/www/html/"
				sh "servie httpd start"
				sh "chmod -R 777 /var/www/html/index.html"
			}
		

			
		}
	}
}
