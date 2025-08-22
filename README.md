## Project Overview

- Heart disease remains one of the leading causes of death worldwide. Due to the food habits, Work culture and stress, the rate of heart diseases are increasing  regardless of age.
- This project focuses solely on increasing and optimizing accuracy of the result. 
- This project applies Algorithms inspired from bio(Metaheuristic)  to select relevant features,evaluate robustness, accuracy and to train predictive models.
- This Project implements multiple algorithms like:<br>
   #### [Aco](aco)
   #### [Bat](bat)
   #### [Bee](bee)
   #### [Ga](ga)
  
## Project Setup & Requirements

- Clone the repo.
- Python version 3.7 should be installed.
- The instructions.txt contains the required libraries which you need to install from CLI.
- cd Heart_Disease_prediction(Choose correct location)
- python Main.py(Run the main script)


## Project Files Exploration

-  Pycache
    - It contains two .pyc files Bat and bee.
    - Python compiled(pyc) speeds up execution by skipping the parsing and compiling steps next time the module is imported.
-  heart_dataset
    -  Dataset_information contains the metadeta.
    -  Url_dataset contains the url to the dataset.
    -  Dataset contains the data used to train the model.
    -  Test contains the data which is used to obtain the result.you can replace the test with actual data.
-  Antcolony Optimization logic
    - Inspired by the foraging behavior of ants and their use of pheromone trails.
    - Excellent for discrete optimization and feature selection tasks.
-  Bat Algorithm
    - Inspired by bAT  mimicing natural behaviors that can adapt to noisy or complex landscapes.
    - Adapts dynamically to locate optimal solutions in continuous domains.Useful for parameter tuning and nonlinear optimization.
-  Bee Algorithm
    - Based on the foraging patterns of honeybees searching for nectar. Combines local search (near good solutions) with global search (random scouts).
    - Effective for multi-modal optimization and feature subset selection.
-  Genetic Algorithm
    - Inspired by natural selection and genetics: selection, crossover, mutation.
    - Great for model optimization, feature selection, and rule generation.
-  Main
