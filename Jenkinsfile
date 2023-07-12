//my 1st jenkins file
pipeline {
	agent {
		label "built-in"
	}
	stages {
	stage ('deploy-one.html') {
		steps {
			sh "cp -r one.html /var/www/html/"
			sh "chmod -R 777 /var/www/html"
}
}
}
}
