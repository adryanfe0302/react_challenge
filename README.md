
# Download docker images.
$ docker pull adryanfernando/code-test-shopee

# Running docker images.
$ docker run -it -p 3000:3000 adryanfernando/code-test-shopee

open your browser and copy paste the link below
http://localhost:3000/



# Build docker images.
$ npm run build
$ docker build . --tag=adryanfernando/code-test-shopee

