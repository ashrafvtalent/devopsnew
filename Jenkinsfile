pipeline{
 agent none
 stages{
 
 stage ('Stage1')
 {
    agent
       {label 'Slave1'}

      
   
    steps {

       sh "cd /home/ubuntu/workspace/pipeline/Myfile1 ; sudo -i"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile1 ; chmod +x stage1.sh"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile1 ; ./stage1.sh"
       
    }

 }

 stage ('Stage2')
 {
    agent 
        { label 'Slave1'}
      
       
    steps {

       sh "cd /home/ubuntu/workspace/pipeline/Myfile1 ; sudo -i"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile1 ; chmod +x stage2.sh"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile1 ; ./stage2.sh"
       
    }

 }

 stage ('Stage3')
 {
    agent 
        { label 'Slave1'}
       
       

    steps {

       sh "cd /home/ubuntu/workspace/pipeline/Myfile1 ; sudo -i"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile1 ; chmod +x stage3.sh"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile1 ; ./stage3.sh"
       
    }

 }

 stage ('Stage4')
 {
    agent 
        { label 'Slave2'}
       
       
    steps {

       sh "cd /home/ubuntu/workspace/pipeline/Myfile2 ; sudo -i"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile2 ; chmod +x stage4.sh"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile2 ; ./stage4.sh"
       
    }
  }

 stage ('Stage5')
 {
    agent 
        { label 'Slave2'}
       
       
    steps {

       sh "cd /home/ubuntu/workspace/pipeline/Myfile2 ; sudo -i"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile2 ; chmod +x stage5.sh"
       sh "cd /home/ubuntu/workspace/pipeline/Myfile2 ; ./stage5.sh"
       
    }

  }

 }

}



