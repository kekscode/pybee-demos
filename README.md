# pybee-demos
some demos for beeware

## batavia

```
$> workon pybee
$> /Users/stefan/PycharmProjects/pybee-demos/pybee-repos/batavia/testserver/manage.py runserver
$> open "http://127.0.0.1:8000"
```

und dort:

```python
print('Set the page title')
dom.document.title = 'Hello CCC-FFM'

print('Find an element on the page...')
div = dom.document.getElementById('stdout')

print('... and set of that element:')
div.innerHTML = div.innerHTML + '\nTest.\n'
```


## Toga

```
$> toga-demo
```

und danach:

```
$> python3.5 toga-browser.py
```

## Briefcase (and Toga)

Create a native app for iOS with briefcase.

```
$> cd ios-app
$> python setup.py ios
```

Then just open the `.xcodeproj` and let it run in a simulator.
