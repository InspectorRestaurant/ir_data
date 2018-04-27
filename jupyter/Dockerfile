# Extends jupyter/datascience-notebook
FROM jupyter/datascience-notebook

# Copies Jupyter notebooks used to format restaurant data
COPY FormatRestaurantsNYState.ipynb /home/jovyan/FormatRestaurantsNYState.ipynb
COPY FormatRestaurantsNYC.ipynb /home/jovyan/FormatRestaurantsNYC.ipynb

# Installs pymongo
RUN pip install pymongo