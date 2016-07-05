# Axovis.Neos.Googlemaps

![alt text](https://raw.githubusercontent.com/axovis/Axovis.Neos.Googlemaps/master/Resources/Public/Images/Neos_GM.jpg "Axovi's Google Maps for Neos")
[![Latest Stable Version](https://poser.pugx.org/axovis/neos-googlemaps/v/stable?format=flat-square)](https://packagist.org/packages/axovis/neos-googlemaps) [![License](https://poser.pugx.org/axovis/neos-googlemaps/license?format=flat-square)](https://packagist.org/packages/axovis/neos-googlemaps)

Easily add a google map anywhere to your website.

The following settings can be done in Neos Inspector:

* Longitude
* Latitude
* Zoomlevel
* Width & height
* Add headline in info window
* Add text to info window
* Width & height for info window
* Define if window should be draggable   

## Install

To install run on your console:

```
composer require axovis/neos-googlemaps
```  

OR add to your composer.json

```
    "require": {
        [...]    
        "axovis/neos-googlemaps": "^2.0"
    },
```
and run `composer update`

Google Maps requires now an API key. You need a Browser Key which has to be added to your projects `Configuration/Settings.yaml` or `Configuration/<Context>/Settings.yaml`. 


[Follow this link for information about how to get the API key from Google Console](https://developers.google.com/maps/documentation/javascript/get-api-key "Google Developers - Get API Key")
