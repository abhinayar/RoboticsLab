# README for "Jem" - A novel animated face robot consturcted for CPSC 473, Spring 2017

## By Abhi Nayar (YC '18), Alex Saointz (YC '18) and Stephanie Hickman (YC '19)

The ReadMe content included in both robot.html and robotControl.html are included below. Please reach out with any questions.

## Robot.hml
Made for CPSC 473, Robotics Lab
  
  By Abhi Nayar, Stephanie Hickman and Alex Saointx
  
  This is the Robot Face code
  
  It is a collection of HTML/CSS/JS that connects to a Firebase backend in order to 
  render on any webpage (any device) a robot face. We also handle the HTML5 Speech API here, which allows our robot to talk.

  
  Firebase account:
    
    The current configuration is set up to access a Firebase account set up by Abhi Nayar
  
    This means it is only accessible by being logged in as him.In order to set this up with your own Firebase account, please follow the following steps:

    1. Create Firebase database in your Console
    
    2. Click on Database, this should take you to the Database Schema
    
    3. It will be blank - what you need to do is manually create the variables
    
    - animationState
    
    - emotiveFace
    
    - emotiveVoice
    
    - endSpeech
    
    - lastQuestion
    
    - reset
    
    - speech
    
    4. Once the schema is created, click on any of the variables and copy the link
    
    5. Replace each variables link
    
    I.E- where it currently says https://jemscazlab.firebaseio.com/variableName
    
    Replace it with https://YOURFIREBASEURL.firebaseio.com/variableName
    
    6. Once you replace all the urls in both robot.html and robotControl.html you should have a persistent database. Now just host robot.html and robotControl.html on a server of your choice and Jem's software should be fully functioning

    NOTE: 
      In interest of time, neither webpage follows W3C specs or has particularly clean code. A TODO would be to move all the CSS and refactor it to a seperate file, as well as seperate out the javascript and just build a cleaner website as a whole. For the purposes of this project however this was more than sufficient.
  
  Thanks!
  
  Abhi, Alex & Stephanie
  
  ## Robot Control
    Made for CPSC 473, Robotics Lab
    
    By Abhi Nayar, Stephanie Hickman and Alex Saointx

    This is the Robot Controller code
    
    It is a collection of HTML/CSS/JS that connects to a Firebase backend in order to render on any webpage (any device) a robot controller. This controller will pass variables into our Firebase backend- variables which will be read by robot.html in order to render the robot face differently or to speak various phrases.

    Firebase account:
      The current configuration is set up to access a Firebase account set up by Abhi Nayar
      
      This means it is only accessible by being logged in as him.
      
      In order to set this up with your own Firebase account, please follow the following steps:

      1. Create Firebase database in your Console
     
     2. Click on Database, this should take you to the Database Schema
      
      3. It will be blank - what you need to do is manually create the variables
      
      - animationState
      
      - emotiveFace
      
      - emotiveVoice
      
      - endSpeech
       
       - lastQuestion
       
       - reset
       
       - speech
      
      4. Once the schema is created, click on any of the variables and copy the link
      
      5. Replace each variables link
        
        I.E- where it currently says https://jemscazlab.firebaseio.com/variableName
        Replace it with https://YOURFIREBASEURL.firebaseio.com/variableName
      
      6. Once you replace all the urls in both robot.html and robotControl.html you should have a persistent database. Now just host robot.html and robotControl.html on a server of your choice and Jem's software should be fully functioning

      NOTE: 
       
       In interest of time, neither webpage follows W3C specs or has particularly clean code. A TODO would be to move all the CSS and refactor it to a seperate file, as well as seperate out the javascript and just build a cleaner website as a whole. For the purposes of this project however this was more than sufficient.

      NOTE2:
        
        This controller can be extended to make Jem speak almost anything (and can also integrate NLP and machine learning to automatically speak things in a trivial manner). 
        
        Edit the data-target of any element having class speech:
          
          <div class="speech speech8" data-target="There is one blue circle.">8</div>
       
       And when this button is pressed that particular data-target phrase will be sent to Jem to speak.

    With any questions feel free to email Abhi Nayar at anayar2[at]gmail[dot]com.

    Thanks!
    
    Abhi, Alex & Stephanie
    
    ## Thank you!