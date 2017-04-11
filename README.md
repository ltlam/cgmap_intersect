# cgmap_intersect
----		
Python script to generate a matrix of methylation values of common CpG sites with a minimum coverage threshold.

----

#### minimum requirements:
1. python 2.7.11 - [https://www.python.org/downloads/release/python-2711/](https://www.python.org/downloads/release/python-2711/)
2. pandas - [https://github.com/pydata/pandas.git](https://github.com/pydata/pandas.git)
4. numpy - [https://sourceforge.net/projects/numpy/files/NumPy/](https://sourceforge.net/projects/numpy/files/NumPy/)

### 1) cgmap_intersect.py

* [in] -in_sam - comma separated list of CGmap file paths
* [in] -out_sam - output file name
* [in] -cov_sam - minimum coverage threshold

```
cd <cgmap_intersect.py path>
python -in_sam ./test_data/PBMC_1.CGmap,./test_data/PBMC_2.CGmap,./test_data/PBMC_3.CGmap,./test_data/PBMC_4.CGmap,./test_data/PBMC_5.CGmap,./test_data/PBMC_6.CGmap -out_sam intersect.txt -cov_sam 10
```
