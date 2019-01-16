### docker-gensim

Gensim docker image based on alpine and python3.6

## run jupyter notebook
docker run -it --rm  -p 8888:8888 -v $(pwd)/data:/code tallestman/gensim