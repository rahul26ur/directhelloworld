node{
   // agent { label 'kubepod' }
      
    stage('SCM Checkout')
    {
        //git url: 'http://172.24.19.82/rahul_cept/dummy.git'
        git url: 'https://github.com/rahul26ur/directhelloworld.git'
    }
    
    
    stage ('Build Stage') 
    {    
         //withMaven(maven : 'maven_3_6_3') {
         // sh 'mvn clean compile'
         //}
        // steps {
          //  withMaven(maven : 'maven_3_6_3') {
            //sh 'mvn clean compile'
            //}   
        // }
         //sh 'mvn clean compile'
         //sh 'mvn install'
         //sh 'mvn package'
        // sh 'mvn clean install'
         //sh "cd /var/lib/jenkins/workspace/rahjava8 \n /usr/bin/mvn clean package spring-boot:repackage"
          //sh "cd /var/lib/jenkins/workspace/rahjava8 \n /usr/bin/mvn clean package"
         //sh "cd /var/lib/jenkins/workspace/rahjava8 \n /usr/bin/mvn clean package  -Dstart-class=com.rah.rest.webservices.rahrestwebservices.helloworld"
         //sh "cd /var/lib/jenkins/workspace/rahjava7 \n /usr/bin/mvn clean package install"
        sh "cd /var/lib/jenkins/workspace/rahdirecthello \n /usr/bin/mvn clean install"
        //sh "cd /var/lib/jenkins/workspace/rahjava7 \n /usr/bin/mvn clean"
        //sh "cd /var/lib/jenkins/workspace/rahjava7 \n /usr/bin/mvn install"
        //sh 'cd /var/lib/jenkins/workspace/rahjava7 \n /usr/bin/mvn clean install'
        
        
      
    }
    /*
    stage('Run Docker Compose File')
    {
        
        sh 'sudo docker-compose build'
        //sh 'sudo docker-compose build'
        sh 'sudo docker-compose up -d'
        //sh 'sudo docker-compose run'
    }
    
    
    stage('Deploy App')
    {
         kubernetesDeploy(configs: "nginx.yaml", kubeconfigId: "mykubeconfig")
    }
    
    stage('PUSH image to Docker Hub')
    {
        withCredentials([string(credentialsId: 'DockerHubPassword', variable: 'DHPWD')]) 
        {
            sh "docker login -u vardhanns -p ${DHPWD}"
        }
        sh 'docker push vardhanns/phpmysql_app'
    }
    */
}

