# mcPixelArt
A simple plugin that allows you to build 2D and 3D structures in Minecraft by simply editing a text file!

# Steps:
1. Download the provided plugin file 'mcPixelArt-1.0-SNAPSHOT' and place it in the 'plugins' folder of your Minecraft server.
2. Create a folder titled 'mcPixelArt' within your 'plugins' folder. 
3. Download the provided 'matrix.txt' file and place it in your mcPixelArt folder. 
4. Edit your 'matrix.txt' file. The first line contains the base coordinates from which the build will begin as well as the orientation of the build.
   Format: x,y,z,orientation , Example: 1053.482,74,-1067.782,1.
6. Use orientation 1 for a flat/horizontal build and orientation 0 for a vertical build (refer to the images below).
7. Edit the matrices (rows of numbers) to create patterns! 0 indicates the absence of a block and any other integer will place a block. The integers should be comma-separated. Each matrix is a separate layer separated by '---'. Different integers represent a different block.
8. Block menu:
   
  i. Stone
  ii. Acacia Planks
  iii. Cyan stained glass\n                     
  iv. Amethyst Block
  v. Basalt  
  vi. Smooth Quartz           
  vii. Gold Block       
  viii. Diamond Block             
  ix. Obsidian    
  x. Black Glazed Terracotta

   
# Please note
1. Written for Minecraft version: 1.21.8
2. DO NOT rename the matrix.txt file.
3. Make sure the folder is named 'mcPixelArt' with no spelling mistakes or changes in the case of the letters, and that it is placed under 'plugins'.

# Example for horizontal build:
INPUT

<img width="437" height="523" alt="image" src="https://github.com/user-attachments/assets/232a7e79-a5a8-4289-8737-c943824539f7" />

OUTPUT

<img width="1920" height="1111" alt="horizontalBuild" src="https://github.com/user-attachments/assets/aac1b5a0-489e-41b9-815a-aca9205e8f0d" />

# Example for vertical build:
INPUT

<img width="427" height="517" alt="image" src="https://github.com/user-attachments/assets/e11a3561-a5a9-4f1f-aaa1-fc1199fbf848" />

OUTPUT

<img width="1920" height="1111" alt="verticalBuild" src="https://github.com/user-attachments/assets/1bd191a7-9152-48ea-b756-a0718cd3c0b3" />


# Tips:
1. Make the patterns in excel and then copy-paste into matrix.txt. Take care to remove the spaces between integers and replace them with commas. Separate each layer/matrix with three hyphens (---) as shown above.
2. To confirm that matrix.txt is in the right location check its path by right-clicking and going to 'properties'. The path will look something like this: D:\test server\plugins\mcPixelArt
3. If you have any questions please feel free to contact me: [LinkedIn](https://www.linkedin.com/in/alicia-gonsalves-9b850124b)

