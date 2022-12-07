FROM ubuntu:18.04
RUN apt -y update
RUN apt -y dist-upgrade
RUN apt -y install --no-install-recommends git wget ca-certificates python3.7 python3-distutils python3-apt
RUN update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.7 10
RUN wget https://bootstrap.pypa.io/get-pip.py
RUN python3.7 get-pip.py
RUN python3 -m pip install --user --no-warn-script-location ansible ansible-core
ENV PATH="${PATH}:/root/.local/bin"
WORKDIR "/repo"
