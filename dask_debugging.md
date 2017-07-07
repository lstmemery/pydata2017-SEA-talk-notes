# Debugging Dask

blocked algorithm

What happens when things don't work

`delayed` makes objects lazy
things that touch a `delayed` object are also lazy
can use delayed as a decorator to make it lazy

%load_ext snakeviz

Dask is pure python (can use pdb)
read_csv is not parallel

dask.multiprocessing

dask.persist stores data in memory
line_profiler also works