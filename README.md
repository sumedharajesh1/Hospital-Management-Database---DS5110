# Hospital-Management-Database---DS5110

Hospital Management Database (with other characteristics)

## How to Run Our Code

1. **Generate the synthetic dataset**: Run the `Main Code for Hospital Database - Final Project - Churou Deng & Sumedha Rajesh.ipynb` file to create your own synthetic dataset with CSV files. It should be noticed that generating 200 doctor notes will take around **4 hours**, and if you are using colab, please run Doctor_note_generator_for_Final_Project.ipynb instead, in case the notebook crashes because of cache limits.
 
2. **Install MySQL**: Download and install MySQL 8.0 from the official website: [https://dev.mysql.com/downloads/]

3. **Build the database schema**: In MySQL Workbench or Shell, execute the `hospitaldb_generation.sql` script to construct the hospitaldb database framework.

4. **Import the data**: Load all the generated CSV files from step 1 into the hospitaldb database tables you created in step 3.

5. **Visualize the data**: Run the `Visualizations for Final Project.ipynb` notebook to create visualizations from your newly created dataset. (If you are running the visualizations in Google Colab, you must load all of the .csv files generated from the `Main Code for Hospital Database - Final Project - Churou Deng & Sumedha Rajesh.ipynb` file into the Visualizations Google Colab file before running it. Otherwise you can simply run the `Visualizations for Final Project.ipynb` notebook in (VS Code) to create visualizations from your newly created dataset.)

## The Schema of Our Database

![ERD](https://github.com/sumedharajesh1/Hospital-Management-Database---DS5110/blob/main/ERD.png)
