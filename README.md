<center>
    <h1>Aya Raytrace Demo</h1>
    <img src="sample.png" />
</center>

An implementation of [Ray Tracing in One Weekend By Peter Shirley](https://raytracing.github.io/).  

## Running

Note: This repo implements the brute-force algorithm from book 1 only and is quite slow. The low resolution render (70x46 pixels) takes about 20 seconds to run. Medium resolution takes a minute or two.

Requires aya >= `0.4-rc1`  
You can get aya from here: https://github.com/aya-lang/aya/releases 


Use the following command to run:

```
aya ray.aya
```


If you do not have aya installed directly, use this command:

```
java -jar aya.jar path/to/aya/install/location ray.aya
```
