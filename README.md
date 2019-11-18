# Really Simple GPS Redirecting

RSGR is as the name implies a really simple HTML solution that redirect a user to the navigation app of their current OS. (Maps on IOS, Google maps on Android or PC) And set the route to the point specified in the URL. 

## How to use
First, you need to add the HTML file to your site. thereafter you can query (the ? sign) the latitude and longitude of the place like so:

```
https://yourdomain.com/path/to/gps.html?lat=<LATITUDE>&long=<LONGITUDE>
```
You can create as many redirect links as you like with the same file, just change the latitude and longitude parameter. 


## Authors

* **Anders Wiggers** - [anders-wiggers](https://github.com/anders-wiggers)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details