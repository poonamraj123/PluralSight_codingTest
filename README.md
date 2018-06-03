# Package Installer Exercise
Jason Gotti
[jason.gotti@gmail.com](mailto:jason.gotti@gmail.com)

Simple use of a topological sort. First create a dictionary then determine order.


## Description
You suddenly have a curious aspiration to create a package installer that can handle dependencies. You want to be able to give the installer a list of packages with dependencies, and have it install the packages in order such that an install won’t fail due to a missing dependency.
This exercise is to write the code that will determine the order of install.

## Exercise Details

[Package Installer Coding Exercise](/PackageInstallerCodingExercise.pdf)

## How to Run Jasmine Tests

```
npm install
```

```
npm start
```

## How to use

Add a reference to the library
```javascript
<script type="text/javascript" src="src/packageInstaller.js"></script>
```
Create an instance of PackageInstaller and run install()
```javascript
var packageInstaller = new PackageInstaller(['a:','a:b']);
var results = packageInstaller.install(); // returns a, b
```
