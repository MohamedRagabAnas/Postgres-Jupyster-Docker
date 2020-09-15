FROM jupyter/datascience-notebook

RUN python --version

RUN conda install --quiet --yes -c \
    conda-forge osmnx dask

RUN pip install -U geopandas \
		   psycopg2

VOLUME /notebooks
WORKDIR /notebooks
