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
