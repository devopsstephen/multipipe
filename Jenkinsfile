pipeline{

     agent any
      tools{
                maven 'mvn-sat'
                jdk 'java-sat'
      }
   stages{

         stage ('checkout') {
             steps {
                 echo "hi"
                 git 'https://github.com/devopsstephen/multipipe.git'
             }
         }


    stage ('Build project') {
       steps {

       sh 'mvn clean package'


   }
}


}



}
