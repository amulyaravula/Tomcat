pipeline {
    agent any 
    stages {
       stage('Switch to Java 17'){
          steps {
              sh '''
                 sudo update-alternatives --set java /usr/lib/jvm/java-17-openjdk-17.0.14.0.7-2.el9.x86_64/bin/java
                 java -version

                 '''
          }
       }
         
      stage('Switch to Java 21'){
        steps {
            sh '''
               sudo update-alternatives --set java /usr/lib/jvm/java-21-openjdk-21.0.6.0.7-2.el9.x86_64/bin/java 
               java -version

               '''
             }
       }
    }
}
   
