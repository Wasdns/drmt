## Run drmt test scripts

### Install Requirments(in Ubuntu 14.04, 64bit)

1.Install Gurobi, see the instructions here:

- English: [Installing Gurobi 7 on Linux](http://abelsiqueira.github.io/blog/installing-gurobi-7-on-linux/)
- Chinese: [Ubuntu 14.04 上安装 Gurobi](http://www.cnblogs.com/qq952693358/p/7445236.html)

2.Install Networkx:

```
$ pip install networkx
```

### Run drmt tests

1.Create a directory(I named `test/` here):

```
$ mkdir test/
```

2.Start running the tests:

```
$ ./run_experiments.sh test/
```

3.See the results in `test/`.
