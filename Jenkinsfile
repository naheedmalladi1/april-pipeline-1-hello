pipeline
{
agent any
stages
{
    stage ('scm-checkout')
    { steps { sh 'echo scm-checkout' }
    }

stage ('compile the code')

    { steps { sh 'echo code compilation' }  
    }

stage ('executing functional & component testing')
    {
        parallel
           stage ('executing functional testing')
              { steps { sh 'echo functional testing' }}
        
           stage ('executing component testing')
              { steps { sh 'echo executing component testing' }}
    }
 }
    
 }
