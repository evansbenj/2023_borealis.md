# Liftoff

get the annotation file for XL
```
wget https://download.xenbase.org/xenbase/Genomics/JGI/Xenla10.1/XENLA_10.1_Xenbase.gtf.gz
```

install liftoff
```
module load gcc python/3.10 minimap2 parasail
virtualenv --no-download --clear ~/ENV && source ~/ENV/bin/activate
pip install git+https://github.com/agshumate/Liftoff.git
```
