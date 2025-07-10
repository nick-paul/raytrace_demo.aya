<center>
    <h1>Aya Raytrace Demo</h1>
    <img src="sample.png" />
</center>

An implementation of [Ray Tracing in One Weekend By Peter Shirley](https://raytracing.github.io/).  

Note: This repo implements the brute-force algorithm from book 1 only and is quite slow. The low resolution render (70x46 pixels) takes a few seconds to run

## Running

Requires aya >= `0.6-SNAPSHOT`
You can get aya from here: https://github.com/aya-lang/aya/releases 

Inside an aya shell, run the following commands to install this package

```
aya> import pkg
aya> "nick-paul/raytrace_demo.aya" pkg.add
```

To run:

```
aya> "raytrace_demo" pkg.run
```


Alternatively , you can clone and run the main file directly

```
cd src
aya main.aya
```
