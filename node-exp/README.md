### Basic Node + Express API

### How to start API

1. Add `.env` file to `node-exp` folder.
2. Add `MONGO_URI=<REMOTE_MONGO_URI>` and `myprivatekey=<RANDOM_LONG_KEY>`
3. Run `npm start`
4. Try hitting `localhost:3000/<endpoints>` using postman or curl or httpie

### How to build image

1. Run `sudo docker build -t <TAG_FOR_IMAGE> .`

### How to run image

1. Run image using `sudo docker run -p 3000:3000 -e MONGO_URI=<REMOTE_MONGO_URI> -e myprivatekey=<RANDOM_LONG_KEY> <IMAGE_ID>`



