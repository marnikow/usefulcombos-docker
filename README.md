# Useful Combo's

This repo consist out of some images that includes standard combos that I myself use. Each image is based on other docker images.

If you would like to have extra combo's, please let me know!

## Combo's

### Python

The current availabe python images are:

- `python-flask`: points to `python3-flask`.
- `python2-flask`: Combo of python 2 extended with flask.
- `python3-flask`: Combo of python 3 extended with flask.

### Java

The current availabe java images are:

- `java8-ant`: points to `java8JDK-ant`.
- `java8JDK-ant`: Combo of java jdk 8 extended with ant.
- `java8JRE-ant`: Combo of java jre 8 extended with ant.

#### Java provided by Oracle

When using the images including java, you must accept the [Oracle Binary Code License Agreement](http://www.oracle.com/technetwork/java/javase/terms/license/index.html) for Java SE.

## Usage

```
docker run -it marnikow/usefulcombos:yourCombo
```
