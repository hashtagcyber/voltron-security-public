# voltron-security-public

Python package for abstracting security findings

Work in Progress

### Test
~~~
git clone git@github.com:hashtagcyber/voltron-security-public.git
cd voltronsecurity
coverage run -m unittest discover -v && coverage report -m --skip-empty --omit 'tests/*'
~~~

### Build
~~~
git clone git@github.com:hashtagcyber/voltron-security-public.git
cd voltronsecurity
python -m build
~~~
### Install
~~~
python -m pip install voltronsecurity
~~~