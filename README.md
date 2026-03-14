# L-arborescence-et-les-fichiers

Voici l'historique pour obtenir les fichiers ainsi que les changer de dossier :


 40 Set-Location -Path C:\...                                                                         
  41 New-Item -path EvenFolder -ItemType Directory                                                     
  42 Get-ChildItem                                                                                     
  43 New-Item -path OddFolder -ItemType Directory                                                      
  44 Get-ChildItem                                                                                     
  45 Set-Location .\FolderTest1                                                                        
  46 Move-Item -Path file2,file4 -Destination C:\EvenFolder                                            
  47 Get-ChildItem                                                                                     
  48 Move-Item -Path file1,file3,file5 -Destination C:\OddFolder                                       
  49 Get-ChildItem                                                                                     
  50 Set-Location C:\FolderTest2                                                                       
  51 Get-ChildItem                                                                                     
  52 Move-Item -Path file6,file8,file10 -Destination C:\EvenFolder                                     
  53 Move-Item -Path file7,file9 -Destination C:\OddFolder                                             
  54 Set-Location                                                                                      
  55 Set-Location C:\OddFolder                                                                         
  56 Get-ChildItem                                                                                     
  57 Set-Location C:\EvenFolder                                                                        
  58 Get-ChildItem     



  Voici le repertoire EvenFolder :

  
