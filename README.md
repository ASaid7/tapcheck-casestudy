# tapcheck-casestudy

## Build the Docker Image

'''bash
docker build -t case-study .
'''

## Run a Jupyter Notebook Server

'''bash
docker run -it --rm -p 8888:8888 -v $(pwd):/app case-study jupyter notebook --ip=0.0.0.0 --allow-root --no-browser
'''
