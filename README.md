# opencv-tutorial-setup-opecv-in-vs

  how to set up opencv in visual studio 20XX(same thing).
    
  download opencv in https://opencv.org/ (any version that you like).
    
  Open your visual studio and create new project ,theN right click your "projectname" in Search program manager.
    
  find the property page at botton , Change your configuration Manager and change to "x64" .
    
  and click on VC++ Directories then find the "Include Directories"  and "Library Directories".
    
  put "your disk:\opencv\build\include;" at last / in "Include Directories" , ";" →This must be added.
    
  then click "Library Directories" and click <Edit> , Paste "C:\opencv\build\x64\vc15\lib".
  
Here is the end in  VC++ Directories

NOW we go to "Linker"→"input"

  click on Additional Dependencies ,edit it.
    
  paste "opencv_world343.lib" and "opencv_world343d.lib" (both you can find in C:\opencv\build\x64\vc15\lib)
    
  all done then try #include <cv2>then you can see. 
    
  
  # PS:備註
   
   C:\opencv\build\include; change where you put your opencv
   
   opencv_world343.lib , 343 is your opencv version like opencv3.4.3
   
   
   
   
