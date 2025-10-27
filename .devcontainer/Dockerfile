FROM mcr.microsoft.com/devcontainers/dotnet:1-8.0-bookworm
USER vscode
RUN sudo apt update && sudo apt-get install -y curl software-properties-common 
RUN curl -sL https://deb.nodesource.com/setup_22.x | sudo bash - 
RUN sudo apt-get install nodejs -y
RUN sudo npm i -g @modelcontextprotocol/inspector