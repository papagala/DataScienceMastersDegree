# Running R, Python and Julia

To achieve this, simply run the following command from this folder.

```bash
docker run -p 10000:8888 -v $PWD:/home/jovyan/work jupyter/datascience-notebook:latest
```