# Data Science Environment Using Docker 
This Dockerfile is specifically designed for students enrolled in Lecturer Kholed Langsari's Data Science course. Built on the Anaconda image, it automates the installation of all necessary packages, dependencies, and Python libraries, providing a hassle-free and consistent environment for class. By using this Dockerfile, students can focus on their studies, without the distractions of configuration and installation.

# Packages installed:
<ul>
    <li>Python</li> 
    <li>Statsmodels</li>
    <li>Pandas</li>
    <li>Numpy</li>
    <li>Seaborn</li>
    <li>Matplotlibs</li>
    <li>Git</li>
    <li>Scikit Learn</li>
    <li>Jupyter</li>
</ul>
<br>

# Software Required: 
<ul>
    <li>Docker desktop App</li> 
    <li>Visual Studio Code</li>
    <li>Terminal</li>
</ul>

# How to pull Your Dockerfile , build image and Run the container :
<ul>
    <li>Initiate the Docker Daemon by launching the Docker desktop application.</li> 
    <li>Proceed to obtain the Docker image from the Remote Repository through the terminal, utilizing the following command:</li>
</ul>
docker pull ahmadwaebeusar/ahmadwbs

<ul>
<il>
Upon completion of the image pull, the image will be ready to run.
<br>
</il>
To run the Docker image you have built earlier, you must execute the following command in the terminal:docker run -d --name (container_name) -p 8000:8000 ahmadwaebeusar/ahmadwbs To run the Docker image in a newly created container and map the container port 8000 to the host port 8000, you can name the container whatever you prefer, but ensure that the image name matches the name of the image you previously built.
</ul>
<br>

# To access the Jupyter's Notebook:
<ul>
<il>
Open Terminal in docker and write jupyter lab --port=xxxx --ip=0.0.0.0 --no-browser --allow-root.
</il>
</ul>
<ul>
<il>
Once your Docker container is up and running, you can access the Jupyter Notebook by entering http://localhost:8000/lab in your web browser.
</il>
</ul>
<image src=jupyter_access.png>

# How to attach the container to Visual Studio Code: 
<ul>
<il>
To utilize VS Code to access code within a container, you must first install the "Dev Container" VS Code extension. This extension enables you to access folders or repositories within a Docker container.
</il>
<il>
After successfully installing the extension, please navigate to the lower-left corner of the window and locate the button labeled "Open a Remote Window," and proceed to click on it to initiate the desired action.
</il>
<il>
Upon clicking the "Open a Remote Window" button, you will be presented with the option to either reopen VS Code in the container or navigate the container and open a folder as per your requirement.
</il>
</ul>

# Create:
Ahmad waebeusar.
