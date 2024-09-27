//This code find the middle point of all odd world on karel IDE

function main(){
   if(frontIsClear()){
       move();
    }
    putBeeper();
    
    while(frontIsClear()){
       move();
    }
    turnAround();
    
    if(frontIsClear()){
       move();
       putBeeper();
    }
    
    while(frontIsClear()){
       move();
       if(beepersPresent()){
          turnAround();
          pickBeeper();
          move();
          putBeeper();
       }
    }
    turnAround();
    
    while(frontIsClear()){
       move();
       if(beepersPresent()){
          turnLeft();
          pickBeeper();
       }
    }
    turnAround();
    
    if(frontIsClear()){
       move();
       putBeeper();
    }
    
    while(frontIsClear()){
       move();
       if(beepersPresent()){
          turnAround();
          pickBeeper();
          move();
          putBeeper();
       }
    }
    turnAround();
    
    while(frontIsClear()){
       move();
       if(beepersPresent()){
          pickBeeper();
       }
    }
    turnAround();
    while(noBeepersPresent()){
       move();
    }
}
