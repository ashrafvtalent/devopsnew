pipeline{
 agent none
 stages{
 
 stage ('Stage1')
 {
    agent { 
       node {label 'Slave1'}
       }
   
    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage1.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage1.sh"
       
    }

 }

 stage ('Stage2')
 {
    agent {
       node { label 'Slave1'}
       }
    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage2.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage2.sh"
       
    }

 }

 stage ('Stage3')
 {
    agent {
       node { label 'Slave1'}
       }

    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage3.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage3.sh"
       
    }

 }

 stage ('Stage4')
 {
    agent {
       node { label 'Slave2'}
       }
    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage4.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage4.sh"
       
    }
  }

 stage ('Stage5')
 {
    agent {
       node { label 'Slave2'}
       }
    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage5.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage5.sh"
       
    }

  }

 }

}



