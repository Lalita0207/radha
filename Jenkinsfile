pipeline{

                agent any
                    
                stages{



                      stage ("stage-1 in 2023q1"){

                             steps {

                               
                                          echo " this is my 1st stage-2023q1"   
                               sleep 25



        }
                      }             
                  stage ("parallel stage") {
                  
                                              parallel {
                                             stage ("stage-2 in 2023q1"){
                                                

                             steps {

                               
                                          echo " this is my 2nd stage-2023q1"  
                               sleep 25


                             }
        } 
                                         stage ("stage-3 in 2023q1"){
                                                

                             steps {

                               
                                          echo " this is my 3rd stage-2023q1"  
                               sleep 25


                             }
        }
         }
      }
    }
  }

