# eanalytics-docker

## About

This image allows to launch jupyter-notebook application and to work on notebooks without having to worry about  dependencies.

## Run
```
 docker run -v $path_2_notebook_folder/:/src/notebooks -p 8888:8888 soloan/eanalytics-jupyter
 ```
Where $path_2_notebook_folder/ is the full path to your notebook folder