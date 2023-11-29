# an.vil
Anvil (stylized as "an.vil") is a set of various libraries written in [EVIL](https://github.com/vddCore/EVIL). The intention is to expand the base functionality of the default EVIL Runtime with features commonly used in programming.

**Note:** These libraries as well as the EVIL Language are still under active development. Breaking changes may occur at any time.



## How can I use this?

The easiest way of installing Anvil is by cloning this repository into a default `include` folder of your EVIL installation. Updating the libraries is as simple as pulling the newest version from the repository, and you can reference all libraries in the repository no matter where your project workspace is located.

In order to use functions provided by Anvil, you can include it in your project with the following line of code:

```evil
val anvil = require("anvil");
```

You can then access all functions through the Table returned by the require call. If you want to use only a specific function or a subset of functions, you can also use this:

```evil
val hash = require("anvil.lib.hash"); // This would import all functions you would usually find under 'anvil.hash'
```

## Where's the documentation?

As of right now, there is none. As this project matures, documentation will be written. For now, the codebase is small enough to be able to understand its features by just checking the code.