FROM node:20-alpine3.19

# INSTALL 'libc6-compat'
RUN apk add --no-cache gcompat

# INSTALL 'libstdc++ & libgcc'
RUN apk add --no-cache libstdc++ libgcc

# INSTALL 'python3' and additional python packages
RUN apk add --no-cache python3 python3-dev py3-pip

# INSTALL 'make, gcc & g++'
RUN apk add --no-cache make gcc g++