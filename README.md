# routeboxer-java
This is a port of Google Maps API RouteBoxer.js in java
http://google-maps-utility-library-v3.googlecode.com/svn/trunk/routeboxer/docs/examples.html

It generates lat/lng boxes for a path from one point to another.

## Installation

Copy this java file into your project

## Usage

```java
double range = 1.60934;  //this is in K
List<LatLng> path = getPath(); //get a list of lat/lng object that describe the route
List<LatLngBounds> results = b.box(path,range);  //returns a list boxes that describe the route
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

1.  Automatically exported from code.google.com/p/routeboxer-java
2.  Fixed bugs in code where the route wasn't boxed correctly when using points via Apple maps and improved algorithm performance


## Credits

Originally ported by Cedric Nicolas, updated by Joe Celano


## License

Eclipse Public License 1.0
