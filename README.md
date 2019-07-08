 
Screens:


This app has 3 View Controllers: 


1 - Travel Locations Map :
Allows the user to drop pins around the world, You can also delete them later,

2- Photo Album View:
Allows the users to download images to add to the album, select what they want to keep and delete the rest. 

3- Deleted Photo View:
show recently removed photos for each photo Album


Foobar is a Python library for dealing with word pluralization.

# virtual tourist Upgrade
This is the last [Udacity](https://www.udacity.com/course/ios-developer-nanodegree--nd003) project. This app allows users to select several  travel locations around the world, and create some photo albums based on the location. The locations and photo albums will be stored using Core Data.

## Requirement:
* 

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)


Requirements to run this app
Versions:

    Xcode 10+
    Swift 4+

Flickr API:

This app uses the Flickr API to get the photos associated to an specific location. In order to use this app, you'll have to provide your own Flickr API key. To configure it, you'll need to add a new file called keys.xcconfig, inside the Supporting Files/Secrets/ folder.

Inside this file you can place your api key like this: FLICKR_API_KEY = YOUR_API_KEY_HERE. There's also a keys.example.xcconfig file you can use to copy this simple configuration.
