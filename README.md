# packaging_tutorial
This is a test repository for publishing a pypi package following the tutorial on https://packaging.python.org/en/latest/tutorials/packaging-projects/. The package is published on TestPyPI https://test.pypi.org/project/example-package-fritzlabs/0.0.1/.

Install the test package with:
```
pip install -i https://test.pypi.org/simple/ example-package-fritzlabs==0.0.1
```

Import the test package with: 
```
from example_package_fritzlabs import example
```

Run the test package function with:
```
example.add_one(2)
```
Which should return `3`

# Example Package

This is a simple example package. You can use
[GitHub-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.
