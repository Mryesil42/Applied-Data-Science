FROM jupyter/datascience-notebook

USER root
# Install lxml
RUN apt-get update \
    && apt-get install -y libxml2-dev libxslt-dev \
    && pip install --no-cache-dir lxml
    
RUN pip install selenium
RUN pip install psycopg2-binary
RUN pip install transformers
RUN pip install tensorflow

USER jovyan


