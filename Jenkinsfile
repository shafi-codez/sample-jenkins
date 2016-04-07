node('slave') {
  stage 'BUILD'
  echo 'Building repo into docker image'
  sh "ls -l *"  
  
  stage 'TEST'
  echo 'Building repo into docker image'
  
  stage 'DEPLOY TO STAG'
  echo 'Building repo into docker image'
  
  input 'Ready to merge to master?' 
  
  stage 'MERGE'
  echo 'Merge Feature to master'
  
  input 'Ready to deploy to prod?' 
  
  stage 'DEPLOY TO PROD'
  echo 'Building repo into docker image'
  
}

node('slave') {
    stage 'Stage 1'
    checkout scm
    echo 'Hello World 1'
    stage 'Stage 2'
    echo 'Hello World 2'
}
