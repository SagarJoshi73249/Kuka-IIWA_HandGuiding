<<<<<<< HEAD
Instruction to set up handguiding for a kuka iiwa robot 
Step 1 is to configure two esm states required to run hand guiding. In ESM 1 you have to configure Hand guiding device enabling state with a Stop 1 reaction. In the configuration, you set only the first enabling switch to true and use the Input CIB_SR.5, these would be pins 18/19 and 28/29 (you can use others if you wish). In ESM 2 it doesn't matter what you configure as long as there is something there (I am using Cartesian velocity monitoring at 1000mm/s and Collision detection at 20Nm).
=======
Guide to Setup handguiding for kuka iiwa robot
>>>>>>> ac80a5aec0c27543f69ae62b458cdbaf5e09a4a9
