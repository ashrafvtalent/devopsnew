pipeline{
 agent{
  label 'Slave1'
 }

 stages{

 stage ('checkout')
 {
     steps {
       checkout scm
 }
 }  
 stage ('Stage1')
 {
    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage1.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage1.sh"
       
    }

 }

 stage ('Stage2')
 {
    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage2.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage2.sh"
       
    }

 }

 stage ('Stage3')
 {
    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage3.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage3.sh"
       
    }

 }

 agent{
  label 'Slave2'
 }

 stage ('Stage4')
 {
    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage4.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage4.sh"
       
    }
  }

  stage ('Stage5')
 {
    steps {

       sh "cd /home/ubuntu/workspace/pipeline1 ; chmod +x stage5.sh"
       sh "cd /home/ubuntu/workspace/pipeline1 ; ./stage5.sh"
       
    }

  }

 }

}



