# install your GitHub repository through "pip install"!!
This is demo repository for "pip install git+githubURL".  
Try install **this repository** with super simple way as below!!  

```bash
pip install "git+https://github.com/tarepan/pipinstallgithub#egg=mypipgh"
```

then use the **mypipgh** package in python as below!!

```python
from mypipgh.checker import hello

hello()
# "hello world, I am from GitHub!!"
```

As common library repository, entire project page itself is not package.  
Instead, **packs** subdirectory is distributable package.  
