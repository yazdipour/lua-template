# Use an official Ubuntu as a parent image
FROM ubuntu:latest

# Install Lua and LuaRocks
RUN apt-get update && apt-get install -y lua5.3 luarocks

# Set the working directory in the container
WORKDIR /workspace

# Copy the project files into the container at /workspace
COPY . /workspace/

# Any additional setup you want to do
# ...
