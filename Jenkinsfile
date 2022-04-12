pipeline
{
agent any   //run stages on nay availavle executor

stages      //it contains all the stages
{
    stage('stage-Clone-the-code')
    {
        steps  {
        sh 'echo code is copying'
        sh 'echo hi,this is dm'}
    }
    stage('stage-execute-unit-test')
    {
        steps{sh 'Executing unit tests' }
    }
    stage('Build-code')
    {
        steps{ sh 'Code id Building'}
    }
   
 }

}



