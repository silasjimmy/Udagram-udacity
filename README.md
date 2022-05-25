# Udagram

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to  process photos using an image filtering microservice. It is a Node-Express application which runs a simple script to process images. [Your assignment]

## Tasks

### Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

### Create a new endpoint in the server.ts file

The starter code has a task for you to complete an endpoint in `./src/server.ts` which uses query parameter to download an image from a public URL, filter the image, and return the result.

We've included a few helper functions to handle some of these concepts and we're importing it for you at the top of the `./src/server.ts`  file.

```typescript
import {filterImageFromURL, deleteLocalFiles} from './util/util';
```

### Deploying your system

Follow the process described in the course to `eb init` a new application and `eb create` a new environment to deploy your image-filter service! Don't forget you can use `eb deploy` to push changes.

## Deployed application
The application is currently available using this [site link](http://udagram-dev-dev.us-east-1.elasticbeanstalk.com). To see the image litering functionality, click this [filterimage link](http://udagram-dev-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://images.pexels.com/photos/45201/kitty-cat-kitten-pet-45201.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500)
