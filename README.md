# utl-classic-editor-comment-out-a-block-of-text
Classic editor comment out a block of text.

    Classic editor comment out a block of text                                                                                   
                                                                                                                                 
    Problem: comment out a block of code                                                                                         
                                                                                                                                 
      Four solutions                                                                                                             
                                                                                                                                 
         1. Command line                                                                                                         
         2. Funtion key                                                                                                          
         3. Mouse action                                                                                                         
         4. Command macro                                                                                                        
                                                                                                                                 
    Hilite lines 3-6  (you need to hilite a blank line before the text - can fix with 'insert' script command)                   
                                                                                                                                 
    This only works in the classic editor(1980s) command line.                                                                   
    Type c ' ' '/*' first;c ' ' '*/' last;  on command line                                                                      
                                                                                                                                 
    https://tinyurl.com/y7v2v6vf                                                                                                 
    https://github.com/rogerjdeangelis/utl-classic-editor-comment-out-a-block-of-text                                            
                                                                                                                                 
    github related posts                                                                                                         
    https://tinyurl.com/y74wdoya                                                                                                 
    https://github.com/rogerjdeangelis?utf8=%E2%9C%93&tab=repositories&q=classic+in%3Aname&type=&language=                       
                                                                                                                                 
    SAS Forum                                                                                                                    
    https://tinyurl.com/ybk74ecn                                                                                                 
    https://communities.sas.com/t5/SAS-Programming/how-to-customize-tools-add-button-for-commenting-out-selected/m-p/521362      
                                                                                                                                 
    Gammers demand instant response to commands. My point and shoot editiong is like                                             
    gamming. It is relavant that you need a gammming mouse, function keys, and hands hovering over critcal keys.                 
    Might be interesting to have contest of SAS programmers to write a 300                                                       
    line program in the least time.                                                                                              
                                                                                                                                 
    COMMAND ===> c ' ' '/*' first;c ' ' '*/' last;                                                                               
                                                                                                                                 
    00001                                                                                                                        
    00002                                                                                                                        
    00003                                                                                                                        
    00004 comment                                                                                                                
    00005 out this                                                                                                               
    00006 block                                                                                                                  
    00007                                                                                                                        
    00008                                                                                                                        
                                                                                                                                 
                                                                                                                                 
    EXAMPLE OUTPUT                                                                                                               
    --------------                                                                                                               
                                                                                                                                 
    COMMAND ===> c ' ' '/*' first;c ' ' '*/' last;                                                                               
                                                                                                                                 
    00001                                                                                                                        
    00002                                                                                                                        
    00003 /*                                                                                                                     
    00004 comment                                                                                                                
    00005 out this                                                                                                               
    00006 block   */                                                                                                             
    00007                                                                                                                        
    00008                                                                                                                        
                                                                                                                                 
    PROCESS                                                                                                                      
    =======                                                                                                                      
                                                                                                                                 
         1. Command line                                                                                                         
                                                                                                                                 
            Type c ' ' '/*' first;c ' ' '*/' last;  on command line                                                              
                                                                                                                                 
         2. Funtion key                                                                                                          
                                                                                                                                 
            F1  c ' ' '/*' first;c ' ' '*/' last;                                                                                
                                                                                                                                 
         3. Mouse action                                                                                                         
                                                                                                                                 
            Purchase Logitech G203 gammimg mouse ($22)                                                                           
            Download  SetPoint6.67.83_smartw10 (in my dropbox)                                                                   
            https://www.dropbox.com/s/bjgtuf8x9pt5e8t/SetPoint6.67.83_smartw10.exe?dl=0      
            
            Map a mouse button to F1  
                                                                                                                                 
         4. Forever command macro (worked for the last 40 years?)                                                                
                                                                                                                                 
               %macro cm / cmd;                                                                                                  
                    c ' ' '/*' first;c ' ' '*/' last;                                                                            
               %mend cm;                                                                                                         
                                                                                                                                 
                                                                                                                                 
                                                                                                                                 
