# Qdrant Getting Started with Python Qdrant Client

## Setting up Qdrant Database with Docker

```
docker pull qdrant/qdrant
docker run -p 6333:6333 qdrant/qdrant
```

## Create a venv and install required packages with pip

```
python -m venv qdrant-venv
```

```
pip install qdrant-client
pip install numpy
pip install Faker
```

## Run main.ipynb jupyter notebook file


### Sources

* https://www.youtube.com/watch?v=2cGM1fEbWJQ - Intro to Qdrant
* https://www.youtube.com/watch?v=LRcZ9pbGnno - Getting started with Qdrant
