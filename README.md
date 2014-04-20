# OpenImageIO bindings for Go

API Status
-----------

* ImageInput - __Partial__
* ImageSpec - __Partial__
* ImageOuput - _Not started_
* ImageBuf - __Partial__
* ImageCache - _Not started_
* ImageBufAlgo - _Not started_
* TextureSystem - _Not started_

Requirements
----------------------

* [OpenImageIO](https://github.com/OpenImageIO)

Installation
------------

This package assumes that OpenImageIO is installed to the standard /usr/local location. 

Default install:

    go get github.com/justinfx/openimageigo

If you have installed OpenImageIO to a custom location, you will need to tell CGO where to find the headers and libs:

    export CGO_CFLAGS="-I/path/to/include" 
	export CGO_LDFLAGS="-L/path/to/lib"

Or just prefixing the install:

	CGO_CFLAGS="-I/usr/local/include" CGO_LDFLAGS="-L/usr/local/lib" go get github.com/justinfx/openimageigo

Documentation
-------------

[http://godoc.org/github.com/justinfx/openimageigo](http://godoc.org/github.com/justinfx/openimageigo)


