# 1st_place_Landslide_Susceptibility

## About
Landslides pose a significant threat to infrastructure, property, and human life on a global scale. The Italian Alps, with their steep slopes and geological characteristics, are particularly vulnerable to such hazards. Thus, the aim of this challenge is to create a landslide susceptibility map for a specific watershed using geospatial environmental datasets and advanced machine learning models. The final output will provide a comprehensive visualisation of the spatial probability of an area being affected by a landslide. This information can greatly assist local authorities in implementing effective mitigation measures to prevent and minimise damages caused by landslides. This product will contribute to the United Nations Sustainable Development Goals 11 and 13, which focus on creating sustainable and resilient cities and combating climate change effects, respectively.

## Objectives:

1. The objective is to establish techniques for landslide susceptibility mapping at a resolution of 5 m/pixel, focusing on shallow landslide types.

2. One of the key challenges is developing an approach for what we can call the zero-case scenario of the training dataset, i.e., regions with no landslide occurrence.

3. To compute the landslide susceptibility map, it is crucial to carefully select and incorporate pertinent environmental factors such as slope angle, aspect, lithology, and others that can significantly impact slope stability.

4. Finally, the accuracy of the proposed method must be thoroughly tested to ensure its reliability in accurately identifying areas with a high probability of landslide occurrence.

## More details about the solution

The unzipped folder contains a lot of files which I will explain.
My challenge in this competition is that I could not use google colab because of the big size of the .tif files.
Also, visualizing and saving the maps took a lot of memory.

After running the codes successfully, if you want to check the maps too, you can uncomment the code if you have a laptop of more than 4gb ram.

### FILES IN THE FOLDER
features_extraction_1.ipynb
features_extraction_2.ipynb
features_extraction_3.ipynb
features_extraction_4.ipynb
train.ipynb
test.ipynb
modelling.ipynb
datasets folder(data from competition)
[then all other maps created by running the code]


### STEPS TO GET A REPRODUCIBLE CODE

In this project, I worked with many libraries and they are mentioned in the requirements.txt. Please, run the code in a jupyter notebook environment,
this is the only environment i could test the model before the deadline for submission of codes.
Ensure, you install all the packages, I chose jupyter notebook as the environment because it has some prebuild or pre-installed packages with it.

To run the code, follow these steps in the correct order.
First run the features_extraction_1.ipynb file, it can take 5 minutes
Then run the features_extraction_2.ipynb file, it can take 5 minutes
Then run the features_extraction_3.ipynb file, it can take 10 minutes
Then run the features_extraction_4.ipynb file, it can take 5 minutes
Then run the train.ipynb file, it can take 2 hours
Then run the train.ipynb file, it can take 5 hours
Then run the modelling.ipynb file, it can take 5 minutes


The result of the model is sub.csv which you will find in the unzipped folder 



