ARG flutter_tag

FROM cirrusci/flutter:$flutter_tag

RUN sudo apt-get update \
    && sudo apt-get install -y chromium-browser \
    && sudo rm -rf /var/lib/apt/lists/*