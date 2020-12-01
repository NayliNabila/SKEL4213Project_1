***get input sound from user***

input sound;

if (sound==FAN);       ***Verify which input user say***
  print ("FAN IS ON");
  
else if (sound==FANoff);
  print ("FAN IS OFF");
  
else if (sound==LAMP);
  print ("LAMP IS ON");
  
else if (sound==LAMPoff);
  print (LAMP IS OFF");
  
else if (sound==CURTAIN);
  print ("CURTAIN IS ON");
  
else if (sound==CURTAINoff);
  print ("CURTAIN IS OFF");
  
else if (sound==RADIO);
  print ("RADIO IS ON");
  
  else if (sound==RADIOoff);
  print ("RADIO IS OFF");
  
else if (sound==TELEVISION);
  print ("TELEVISION IS ON");
    
else if (sound==TELEVISIONoff);
  print ("TELEVISION IS OFF");
  
else 
  print ("INVALID INSTRUCTIONS");
