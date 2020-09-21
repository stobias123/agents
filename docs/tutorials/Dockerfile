FROM quay.io/kubeflow/tf-notebook-image:v0.7.0
USER root
RUN apt-get install -y xvfb ffmpeg && \
    pip install 'gym==0.10.11' && \
    pip install 'imageio==2.4.0' && \
    pip install PILLOW && \
    pip install 'pyglet==1.3.2' && \
    pip install pyvirtualdisplay && \
    pip install tf-agents
USER jovyan