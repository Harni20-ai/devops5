pipeline { 
 agent any 
 
 stages { 
 
  stage('Clone') { 
   steps { 
    git 'https://github.com/Harni20-ai/devops5.git' 
   } 
  } 
 
  stage('Install') { 
   steps { 
    bat 'npm install' 
   } 
  } 
 
  stage('Run App') { 
   steps { 
    bat 'node app.js' 
   } 
  } 
 
  stage('Test') { 
   steps { 
    bat 'npm test' 
   } 
  } 
 
 } 
} 