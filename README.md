# Flippo Navigation

[![pub package](https://img.shields.io/badge/pub-0.0.5-green.svg)](https://pub.dartlang.org/packages/flippo_navigation)

Flippo Navigation- A Flutter Package for an animated navigation drawer.

<p>
	<img src="https://github.com/sad1996/flippo/blob/master/Screenshot/Screen1.png?raw=true" width="250" height="443"  />
	<img src="https://github.com/sad1996/flippo/blob/master/Screenshot/Screen2.png?raw=true" width="250" height="443" />
</p>

## How to use

````dart
import 'package:flippo_navigation/flippo_navigation.dart';
````

Create an animated navigation drawer with the following snippet:

````dart
new Flippo(
      mask: new Scaffold(
        backgroundColor: Colors.white,
      ),
      body: new Scaffold(
        backgroundColor: Colors.white,
      ),
      drawer: new Scaffold(
        backgroundColor: Colors.black,
      ),
    );
````