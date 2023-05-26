# Data-Processing-in-Python---JEM207
This repository is created for the course "Data Processing in Python - JEM207". Summer semester 2023
# External Military Aid in Ukraine
## Project Description
The main purpose of this project is to find a correlation between external military aid and liberated territories and try to predict when the war will be over if there is a correlation. So, we are trying to answer two questions: Do the military aid from the US and the 9 countries of NATO help Ukraine to liberate Ukrainian territories? Is there a difference in military aid between these countries? <br />
The answers to these questions are estimated in the file [External Military Aid in Ukraine](https://github.com/Vlad-ies/Data-Processing-in-Python---JEM207/blob/main/External%20Military%20Aid%20in%20Ukraine.ipynb) <br />
Our project consists of two parts:
1. For the first part, we used data from Kaggle(https://www.kaggle.com/datasets/piterfm/2022-ukraine-russian-war). Two datasets show Russian losses as military equipment and as casualties. We visualized it and in addition, calculated how much equipment was destroyed and remaining for the Russian side by April 2, 2023.
2. For the second part,  we used our dataset for panel data to find the answers tour questions above. If there is a significant correlation between military aid and liberated territories, it might be possible in the future to predict when the war will be over. <br />
Our main tests were conducted for territory because the  (territory) is a factor of production, which is a crucial element in creating goods and services. Ukrainian soil (chernozems) is very fertile and plays one of the most important roles in agricultural activities, not only in Ukraine but all over the world. Because Ukrainian chernozems are about 9% of the world's reserves, and 30% of European reserves, and cover an area of about 27 million hectares (46% of the country). Ukraine ranks fourth in the world after Russia, the U.S., and China in the area of chernozems. <br />
Ukraine is rich in natural resources such as coal, iron ore, manganese, nickel and uranium, and many other natural resources. Sulfur reserves are the largest in the world, and mercury ores (cinnabar) are the second largest in the world, as well as Ukraine, which has more than 5% of the world's iron ores.  <br />
Therefore, the territory is a very important economic issue during the war that is now taking place in Ukraine. That's why this work was proposed to understand if foreign military aid helps reclaim the territory back or not.  <br />
This project is using panel data and it was shown some expected differences between the military aid by the US and 9 countries of NATO.  <br />
All information regarding the project: a description of the datasets, a very detailed explanation of the results we got, a step-by-step algorithm of all our actions, and finally conclusions are in the file [External Military Aid in Ukraine](https://github.com/Vlad-ies/Data-Processing-in-Python---JEM207/blob/main/External%20Military%20Aid%20in%20Ukraine.ipynb).   <br />
## Description of the files and how to use the project
[External Military Aid in Ukraine](https://github.com/Vlad-ies/Data-Processing-in-Python---JEM207/blob/main/External%20Military%20Aid%20in%20Ukraine.ipynb) - main file with all the information. <br />
[russia_losses_equipment.csv](https://github.com/Vlad-ies/Data-Processing-in-Python---JEM207/blob/main/russia_losses_equipment.csv) - Russian losses military equipment.  <br />
[russia_losses_personnel.csv](https://github.com/Vlad-ies/Data-Processing-in-Python---JEM207/blob/main/russia_losses_personnel.csv) - Casualties of the Russian troops.  <br />
[aid.csv](https://github.com/Vlad-ies/Data-Processing-in-Python---JEM207/blob/main/aid.csv) - own dataset for Panel data(US and Europe military help). <br />
Download each file and change the path to 3 datasets in the main file "External Military Aid in Ukraine".  <br />
## Framework
We have panel data which means data from many units (variables), over many points in time. Panel data contains statistical information about the same set of objects in a series of successive periods. We used pooled regression, the fixed effects model, and the random effects model. A balanced panel is used (there is no missing data). The appropriate tests were used as well.
## Contribution
If you wish to contribute, kindly adhere to the following instructions:
1. Begin by forking the repository.
2. Generate a new branch dedicated to your modifications.
3. Implement the changes and commit them to your branch.
4. Finally, submit a pull request to the development branch.
## License, requirements, and .gitignore
The license is used: "GNU General Public License v3.0" also it was added requirements and .gitignore.
