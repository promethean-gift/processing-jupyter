# processing-jupyter

Jupyter Notebooks for processing lidar and sfm-mvs point cloud data

# containers

Our analyses were run using Docker containers on NSF CyVerse and University of Arizona cyberinfrastructure.

After you create a [CyVerse Account](https://user.cyverse.org/) (free), you can launch the container used in our analyses here: <a href="https://de.cyverse.org/de/?type=quick-launch&quick-launch-id=63afd24c-9acc-4a8c-85ef-58b634a2ebc2&app-id=c940912c-fcea-11ea-b07f-008cfa5ae621" target="_blank"><img src="https://de.cyverse.org/Powered-By-CyVerse-blue.svg"></a>

Alternately, you can install [Docker](https://docker.com) and run the analysis on your local computer:

```
docker run -it --rm -p 8888:8888 -v /home/<your-username>:/data/ -e REDIRECT_URL=http://localhost:8888 cyversevice/jupyterlab-geospatial:latest
```

Open your browser and navigate to `localhost:8888`

# steps

Clone this repository in the Jupyter Lab, using the Terminal:

```
git clone https://github.com/promethean-gift/processing-jupyter
```

Open the `*.ipynb` notebooks, some steps are run on the Terminal command line.

Follow the steps or modify the code in the `.geojson` or `.ipynb` files to change and to select new data sets.
