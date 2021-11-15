# renum-nodes
This repo renumbers nodes so that neighboring ranks are mapped to neighboring nodes (stride = 1).

## Prerequisite
* pandas
* networkx

## Run
```shell
$ python3 renum-nodes.py -f <edgefile> -s <stride> //default stride = 1
```

* Given 1 2 3 4 5 6 7 8 9 10, if stride = 1 (default), then 1 2 3 4 5 6 7 8 9 10
* if stride = 2, then 1 3 5 7 9 2 4 6 8 10
* if stride = 3, then 1 4 7 10 2 5 8 3 6 9

## Source Files
### [renum-nodes.py](renum-nodes.py)
* This is the main program.
