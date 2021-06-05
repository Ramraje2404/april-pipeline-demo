pipeline
{
agent any
stages
{ stage ('sch checkout')
  {  steps { sh 'echo code_is_downloading'} 
  }

  stage('please build the code')
  { steps {  sh 'echo code_is_building' } 
  }
 
   stage('please deploy the code on qa')
  { steps {  sh 'echo code_is_deploying on qa' } 
  }
 
    stage('please deploy the code on prd')
  { steps {  sh 'echo code_is_deploying on prd' } 
  }
}
}
