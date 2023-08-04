node {

   stage('SCM') {
      // git clone
	  git 'https://github.com/gudidha/spring-petclinic.git'
   }
   
   stage ('build the packages') {
      // mvn compile
	  sh 'mvn compile'
   }

   
   
   stage ('archival') {
     // archiving artifacts
	 archive 'target/*.jar'
   }

}
