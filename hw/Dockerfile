FROM jupyter/minimal-notebook:1386e2046833

COPY requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt && \
    fix-permissions $CONDA_DIR && \
    fix-permissions /home/$NB_USER
