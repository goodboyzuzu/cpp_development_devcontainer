FROM mcr.microsoft.com/devcontainers/cpp:0-ubuntu-22.04


# [Optional] Uncomment this section to install additional packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>
RUN apt-get update && apt-get install -y doxygen && apt-get install -y freeglut3-dev
RUN apt install libeigen3-dev -y
RUN apt install -y libopencv-dev
RUN apt install -y g++-10 && update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-10 100 && update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-10 100