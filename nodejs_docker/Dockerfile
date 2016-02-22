FROM nodesource/vivid:4.2.1
ENV NODE_ENV dev
# cache package.json and node_modules to speed up builds
ADD package.json package.json
RUN npm install

# Add your source files
ADD . .
EXPOSE 3000
