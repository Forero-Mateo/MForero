# Project Portfolio

Hello, thank you for visiting my project portfolio. This is a small list of projects completed by me over the years. I plan to continue adding old and new projects to this webpage. Each project title will link to the GitHub repository it is stored in, where you can read a bit more about the project and look through the code as well.

## Graduate Project

### [Stroke Prediction and Inference in R and Python](https://github.com/Forero-Mateo/Stroke_Prediction_and_Inference)
This was a project for the graduate course Applied Data Mining and Analytics in Business. It uses the [Stroke Prediction Dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset) found on Kaggle. The dataset was adjusted to only include adults (Age >= 18) because the risk factors associated with stroke in adolescents and children, such as genetic bleeding disorders, are not captured by this dataset.

The goal of the project was to execute data exploration and model creation in the hope of building a risk measure comparable to the physician established CHADS-VAS Score. This tool uses age, biological gender, presence of congestive heart failure, hypertension, history of strokes, heart disease and diabetes to predict risk of stroke. Creating a model that uses similar variables in addition to adding social determinants of health such as marriage status, work type, and residence type may provide a better prediction than is currently being used.

![](https://raw.githubusercontent.com/Forero-Mateo/Stroke_Prediction_and_Inference/main/Stroke_Data-Mining_files/figure-gfm/unnamed-chunk-8-1.png)<!-- -->

### [RShiny App - Housing Market Dashboard](https://mforero.shinyapps.io/hw5_forero_mateo/)
This was a project for the graduate course Data Visualization. It allows for interactive plots using reactive R language to compare the housing market in the last decade for each state. The motivation for this dashboard was to give an overview of each states housing market that a novice user can understand. The user can select the state they are interested in looking at and use the date slider to zoom in to specific time ranges. This trend shows how different residential properties have increased in value over the last 10 years. Redfin collects the data in a per month bases (i.e median sale price for Jan-2019). 
![](https://github.com/Forero-Mateo/RShiny_House_Market/blob/main/RshinyApp.PNG)


## Undergraduate Projects

### [Ammonia Production Model and Optimization](https://github.com/Forero-Mateo/Kinetics_Ammonia_Production)
This was a project for the senior level course Kinetics and Reactor Design to model and design an autothermic reactor for ammonia production. Three different reactor models were created to demonstrate how each scenario could impact conversion and design parameters. Model design required building design equations, solving systems of ODEs, solving systems of linear equations (e.g., energy balance, net rate equations, gas heat capacities), and parameter optimization. All model design was done using MATLAB

![](https://raw.githubusercontent.com/Forero-Mateo/Kinetics_Ammonia_Production/main/Plots/PD_Temp.png)

### [Iterative Mass and Energy Balance](https://github.com/Forero-Mateo/Mass_Energy_Balance)
This was a project for the junior level course Mass and Energy Balance II to solve a system of linear equations iteratively for an underdetermined system (recycle stream). Originally the project scope asked to solve for all unknown values for 3 different temperatures using Excels "Goal Seek" but having taught myself MATLAB the summer leading to this class, I chose to complete this project on MATLAB and solved for all 150 possible answers. 

The main purpose of demonstrating this project is to present the self-taught coding style and the numerical methods utilized (matrix algebra, solving underdetermined systems, advanced calculus etc.) to solve problems.
