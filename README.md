# HelloVR
Hello Wold VR application for corto

## Building
If you do not yet have corto installed, do:
```
curl https://corto.io/install-dev-src | sh
```

Then, install the VR UI extension by doing:
```
git clone https://github.com/cortoproject/driver-ui-vr
bake driver-ui-vr
```
Then, download and build this project, by doing:
```
git clone https://github.com/SanderMertens/HelloVR
bake HelloVR
```
You can now run the project from anywhere on your machine, by doing:
```
corto run HelloVR --interactive
```
After you run the project, go to http://localhost:9090, and click on the two stacked squares icon. Then make sure you are monitoring the data scope by clicking on the compas icon next to the query bar. You should see two squares hovering above a gray plane against a dark background, like this:

![screenshot](https://github.com/cortoproject/driver-ui-vr/blob/master/images/screenshot.png)
