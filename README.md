CSH Datto Bootstrap
=======================

A [Bootstrap](http://getbootstrap.com) material theme designed for use on [Computer Science House](http://csh.rit.edu) websites. Based on [Materia](https://bootswatch.com/materia) by [Bootswatch](https://bootswatch.com) and Datto theming.

Demo
----

A live demo of this theme that showcases most components can be found [here](https://s3.csh.rit.edu/csh-datto-bootstrap/4.0.0/index.html).

Usage
------
You can choose to install this package with NPM, or simply include the CDN links on your webpage. In both cases, you must still include Bootstrap's required JavaScript libraries to have functional dropdowns, modals, etc. unless you are using an alternative implementation (e.g. [Reactstrap](http://reactstrap.github.io)).

#### Installation
CSH Dato Bootstrap is available via NPM. This method is recommended for modern web applications. Simply run the following command to add the package to your project:

```
npm install --save csh-datto-bootstrap
```

You can then include the stylesheet into your bundled project:

```
import 'csh-datto-bootstrap/dist/csh-datto-bootstrap.css';
```

Or with SCSS:

```
@import "node_modules/csh-datto-bootstrap/src/csh-datto-bootstrap.scss";
```

#### CDN
Use CSH Datto Bootstrap without a package manager.

###### CSS

```
<link rel="stylesheet" href="https://s3.csh.rit.edu/csh-datto-bootstrap/4.0.0/dist/csh-datto-bootstrap.min.css" media="screen">
```

###### JS, Popper.js, and jQuery

```
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-a5N7Y/aK3qNeh15eJKGWxsqtnX/wWdSZSKp+81YjTmS15nvnvxKHuzaWwXHDli+4" crossorigin="anonymous"></script>
```

Development
------------
You must have [Node 6 or higher](https://nodejs.org) and NPM or [Yarn](https://yarnpkg.com) installed.

Once you have those tools installed, clone this repo and run the following command to install dependencies:

```
npm install
```

Or, with Yarn:

```
yarn
```

Once all of the dependencies are installed, run `npm build` to build the stylesheet (artifacts will be dropped in `./dist`), or `npm start` to watch the source files for development.


Contributing
-------------
**Issues:** Provide a detailed report of any bugs you encounter and open an issue on [GitHub](https://github.com/ComputerScienceHouse/csh-datto-bootstrap/issues). Screenshots are appreciated!

**Code:** Fork this repo, make a fix, and submit it as a pull request.
