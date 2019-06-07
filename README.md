# pip-staticify
Simple python-pip tool to make your requirements.txt file static (versioning)

Totally usefull, we all know the struggle of not wanting to overwrite all requirements in your requirements.txt!

##But how do i get it?

``pip install --upgrade pip-staticify``

``staticify requirements.txt``

And it's magic, all the requirements from your requirements.txt are versioned!


### Notes to future self
Because you for sure are gonna forget how you upload a new version..

`python3 setup.py sdist bdist_wheel`

`python3 -m twine upload dist/*`

## bugs?

Yeah that sucks, please let me know in the issue section.. maybe i will fix it.