# chignolin input files for molecular dynamics simulation.

Repository for teaching beginners what is molecular dynamics simulation

## Jupyter notebook

```
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/work matsunagalab/openmm
```

## Execute a script

```
docker run --rm -v "$PWD":/work matsunagalab/openmm python -u run.py
```

