This tutorial was presented at the FOCiS convention at 2024 in San Fransisco, and was developed by the ImmPort team and UCSF.
This is a tutorial on how to use AI tools such as chat GPT in combination with Python in a Jupyter lab enviornment.
There is the PDF slideshow of how to use this tutorial, with videos that show each step.
Part 1(Part 2 in the slideshow) is the exploratory analysis, where we explore our Vacine response dataset downloaded from immpornt.
Part 2(Part 4 in the slideshow) is the statistical analysis, where we run some analysis on ELISA data, and compare vacine response between the LAIV and TIV vaccine types, 
and also within different demographic groups.
We have an additional tutorial on how we used the API to download data in the ApiTutorial folder

Running JupyterLab with Docker
To run the JupyterLab environment with the provided notebooks:

Pull the Docker image:

docker pull yusufashk/immportworkshop2024:latest

Run the Docker container:

docker run -p 8888:8888 yusufashk/immportworkshop2024:latest

Access JupyterLab:

Open a web browser and navigate to http://localhost:8888. You should see the JupyterLab interface with the provided notebooks available.

Contact yusufashk@gmail.com for any questions about this tutorial

Thanks to Reuben Sarwal for helping create this tutorial, and Sanchita Bhattacharya for her supervision in this whole process. Also thanks to the rest of the import team for their help in stress testing and their efforts to optimize the tutorial.
