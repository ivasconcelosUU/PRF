# PRF

## installation:

clone the repository and from PRF\ run
```
python setup.py install
```

## example usage   
```
from PRF import prf
prf_cls = prf(n_estimators=10,  bootstrap=True, keep_proba=0.05)
prf_cls.fit(X=X, dX=dX,y=y)
pred = prf_cls.predict(X=X, dX=dX)
```

also see PRF/examples folder:

https://nbviewer.jupyter.org/github/ireis/PRF/blob/master/PRF/examples/PRF_for_missing_data.ipynb

## Authors

* **Itamar Reis** - https://github.com/ireis

* **Dalya Baron** - https://github.com/dalya

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
