# Black with 2 spaces

Black claims itself as uncompromising PEP8 compliant formatter, but as you can see on the [.flake8](https://github.com/chrischoy/black2/blob/master/.flake8), it already made some compromises. However, they are unwilling to compromise on the 4 space "guideline".

For those who got annoyed by https://github.com/psf/black/issues/378, install `black2` for black with 2 space indent with

```
pip install git+https://github.com/chrischoy/black2
```

Or in your project, you can add this line to your `requirements.txt`

```
git+https://github.com/chrischoy/black2
```

and

```
pip install -r requirements.txt
```

## Usage


```
black2 <python_file.py>
```

# Links

- <a href="https://github.com/psf/black/">Black</a>
