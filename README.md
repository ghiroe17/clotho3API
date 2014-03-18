# Clotho 3.0   <img align="right" src="http://cidarlab.org/wp-content/uploads/2013/08/research-clotho.png" />
<!-- ![](http://cidarlab.org/wp-content/uploads/2013/08/research-clotho.png) -->

## Purpose

## Getting Started

### Installation
+ **Requirements:** 
    1. Kristopher Kowal's [Q Promise Library](https://github.com/kriskowal/q) for asynchronous server communication.<br />
    *Simplest Approach: Copy and paste the following source script into your HTML's head.*
    `<script type="text/javascript" src="//cdnjs.cloudflare.com/ajax/libs/q.js/0.9.6/q.min.js"></script>` 
    
    2. **clotho3api.js:** Download the Clotho API, add it to your project files, and include it as a `<script>` tag within your HTML (loading this script will create a `Clotho` global variable which is used to call any of the listed Clotho functions below).
    
    3. **Install Clotho:** Follow the instructions outlined [here](https://github.com/CIDARLAB/clotho3/wiki/Installing-Clotho-3.0).

### Resources
* [Q Promise Reference](https://github.com/kriskowal/q/wiki/API-Reference)
* [Official Clotho Website](http://www.clothocad.org/)
* [About Clotho](http://cidarlab.org/clotho/)

## API
### .create()
> Creates new Clotho object.

### .destroy()
> Destroys specified Clotho object.

### .set()
> Sets one or multiple key-values for the specified Clotho object.

### .get()
> Gets a specified Clotho object.  

### .query()
> Queries for all Clotho objects matching the specified criteria.

### .queryOne()
> Queries for any single Clotho object matching the specified criteria.

### .run()
> Runs a specified function with the given input parameters.

### .submit()
> Runs the input script.

### .login()
> Attempts to log in with the specified *username* and *password*.

### .logout()
> Attempts to log out if a user is currently logged in.

## Examples

## Tests
TODO: Add a link to the Q test suite HTML (use rawgithub or htmlpreview)

## Contact

![](http://cidarlab.org/wp-content/uploads/2013/08/logo-adjusted.png)