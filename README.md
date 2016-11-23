# ngx_http_image_filter_module

## Introduction

The module   adjust image orientation automatically when  resize image .
There is a conflict between it and http://nginx.org/en/docs/http/ngx_http_image_filter_module.html.

## Installation
### install dependencies
- Ubuntu/debain

sudo apt-get install libgd-dev

sudo apt-get install libexif-dev

- centos/redhat

sudo yum install gd gd-devel 

sudo yum install libexif-devel

### install module

 ./configure --add-module=/path/to/ngx_http_image_filter_module
 
 
 
## Configuration

see [ngx_http_image_filter_module](http://nginx.org/en/docs/http/ngx_http_image_filter_module.html)
