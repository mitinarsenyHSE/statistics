# HomeWork
## Usage
### Build
```bash
docker build -t mitinarsenyhse/stat:hw-latest .
docker push mitinarsenyhse/stat:hw-latest
```
### Run
```bash
docker run --rm \
    -v "${PWD}":/home/jovyan/work \
    -p 8888:8888 \
    mitinarsenyhse/stat:hw-latest
```
