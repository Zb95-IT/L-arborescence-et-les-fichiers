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



  Voici le repertoire EvenFolder ainsi que OddFolder :

  PS C:\EvenFolder> Get-ChildItem


    Répertoire : C:\EvenFolder


Mode                 LastWriteTime         Length Name                                                 
----                 -------------         ------ ----                                                 
-a----        14/03/2026     19:56              0 file10                                               
-a----        14/03/2026     19:56              0 file2                                                
-a----        14/03/2026     19:56              0 file4                                                
-a----        14/03/2026     19:56              0 file6                                                
-a----        14/03/2026     19:56              0 file8                                                
-a----        14/03/2026     20:31          12614 Historiqueexofolder.txt   




----------------------------------------------------------------------------------
PS C:\OddFolder> Get-ChildItem


    Répertoire : C:\OddFolder


Mode                 LastWriteTime         Length Name                                                 
----                 -------------         ------ ----                                                 
-a----        14/03/2026     19:56              0 file1                                                
-a----        14/03/2026     19:56              0 file3                                                
-a----        14/03/2026     19:56              0 file5                                                
-a----        14/03/2026     19:56              0 file7                                                
-a----        14/03/2026     19:56              0 file9                                                






  

  
