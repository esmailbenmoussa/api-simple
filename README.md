fastapi dev main.py

### The container will run with this:

fastapi run main.py --host 0.0.0.0 --port 8000

## Docker container setup

### Build the image

`docker build -t fastapi-simple .`

### Run the container

`docker run -p 8000:8000 fastapi-simple`
