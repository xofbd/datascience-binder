# Python environment with a requirements.txt

[![Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/xofbd/datascience-binder/HEAD)

A Binder-compatible repo with a `requirements.txt` file.

Access this Binder at the following URL

https://mybinder.org/v2/gh/xofbd/datascience-binder/HEAD

## Notes
The `requirements.txt` file should list all Python libraries that your notebooks
depend on, and they will be installed using:

```
pip install -r requirements.txt
```

The base Binder image contains no extra dependencies, so be as
explicit as possible in defining the packages that you need. This includes
specifying explicit versions wherever possible.

If you do specify strict versions, it is important to do so for *all*
your dependencies, not just direct dependencies.
Strictly specifying only some dependencies is a recipe for environments
breaking over time.
