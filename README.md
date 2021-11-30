# Basic_nodeApp_Container-

you first need to install [Docker](https://www.docker.com/products/docker-desktop)

## Installation

Download the code source and open your terminal and open the Basic_nodeApp_Container- directory 

## Usage

```python
docker build -t my-node-app .
docker run --init --publish 3000:3000 my-node-app
```
if followed the steps correctly the node application will start running at port:3000 [click here](http://localhost:3000)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
