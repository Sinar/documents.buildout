# Documents Buildout

A Plone buildout with DocumentCloud viewer and annotation support

# Requirements

## Ubuntu/Debian Linux
 
 * graphicsmagick
 * tesseract-ocr
 * build-essential
 * python-dev

# Setup

 * setup virtualenv with python 2.7
 * <virtualenv>/bin/python bootstrap-buildout.py

For docsplit: gem install docsplit

# Running Debug mode

 * bin/zeoserver start #zeo database
 * bin/instance fg  #zope instance
 * bin/pcelery worker etc/parts/instance/etc/zope.conf

