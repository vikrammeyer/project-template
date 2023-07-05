# {{ cookiecutter.project }}

- `chmod +x env.sh` and then `./env.sh` to setup project env

- Use the following snippet in Jupyter notebooks to auto reload any changes to your package:

```
%load_ext autoreload
%autoreload 2
from pkg.module import Class, function
```