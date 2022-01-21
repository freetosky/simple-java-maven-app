<<<<<<< HEAD
pipeline{
  agent {
   docker {
	image 'maven:3-alpine'
	args '-v /root/.m2::/root/.m2'
}
}
 stages {
	state('Build') {
	steps {
	sh 'mvn -B -DskipTests clean package'

}
}
}
=======
pipeline {
    agent {
        docker {
            image 'maven:3-alpine' 
            args '-v /root/.m2:/root/.m2' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
>>>>>>> 767e3bbe33c995dcaf1af2942da3737c302632bf
}
