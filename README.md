Simple performance test for webpack 5 and Vaadin 14.1, 14.2

To run the 14.1 test, do
```
git checkout 141
rm -rf node_modules target
mvn # This makes sure all dependencies are downloaded
# ctrl-c when started
rm -rf node_modules target
mvn
# Check the startup time from the "Started Application in XXX seconds" output
# Record the time as "install node_modules + webpack"
# ctrl-c
mvn
# Record the time as "webpack"
```

To run the 14.2 test, do
```
git checkout 142
rm -rf node_modules target
mvn # This makes sure all dependencies are downloaded
# ctrl-c when started
rm -rf node_modules target
mvn
# Check the startup time from the "Started Application in XXX seconds" output
# Record the time as "install node_modules + webpack"
# ctrl-c
mvn
# Record the time as "webpack"
```

To run the 14.2 + webpack 5 test, do
```
git checkout 142-webpack5
rm -rf node_modules target
mvn # This makes sure all dependencies are downloaded
# ctrl-c when started
rm -rf node_modules target
mvn
# Check the startup time from the "Started Application in XXX seconds" output
# Record the time as "install node_modules + webpack"
# ctrl-c
mvn
# Record the time as "webpack"
```

