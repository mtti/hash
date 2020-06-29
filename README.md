[![Made with Unity](https://img.shields.io/badge/Made%20with-Unity-333.svg?style=flat-square&logo=unity)](https://unity.com/)

Hash function implementations by various authors (see below) repackaged as a Unity package. These are useful for procedural generation and making them available in this repo makes it easy for me to use them in my projects.

I've modified the original code slightly by wrapping it in a `mtti.Hash` namespace for safety.

This repository is unlikely to be updated as I've been using this same unchanged code for years.

## Authors

Parts of this repository are covered by different licenses.

* This repository assembled an maintained by Matti Hiltunen &copy;2020.
  * CC0 1.0 Public Domain Dedication (https://creativecommons.org/publicdomain/zero/1.0/) in so far as any of my minor contributions to this repo are covered by copyright.
* C# implementation of xxHash optimized for producing random numbers from one or more input integers. Copyright &copy;2015, Rune Skovbo Johansen. (https://bitbucket.org/runevision/random-numbers-testing/)
  * Mozilla Public License, v. 2.0. (http://mozilla.org/MPL/2.0/).
* Based on C# implementation Copyright &copy;2014, Seok-Ju, Yun. (https://github.com/noricube/xxHashSharp)
  * BSD 2-Clause License (http://www.opensource.org/licenses/bsd-license.php)
* Original C Implementation Copyright &copy;2012-2014, Yann Collet. (https://code.google.com/p/xxhash/)
  * BSD 2-Clause License (http://www.opensource.org/licenses/bsd-license.php)
