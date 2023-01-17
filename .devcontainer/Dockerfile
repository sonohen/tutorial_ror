FROM mcr.microsoft.com/devcontainers/base:jammy
RUN apt -y update && apt -y upgrade
RUN apt -y install gcc make git
RUN apt -y install ruby sqlite3 nodejs yarn
RUN apt -y install ruby-dev libsqlite3-dev
RUN gem install rails