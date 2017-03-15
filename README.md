

╰➔ git tag 0.1 -m "Adds a tag so that we can put this on PyPI."
╰➔ git push --tags origin master

╰➔ python setup.py register -r pypitest 
╰➔ python setup.py sdist upload -r pypitest  