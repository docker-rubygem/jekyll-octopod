[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/jekyll-octopod.svg)](https://hub.docker.com/r/rubygem/jekyll-octopod/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/jekyll-octopod.svg)](https://hub.docker.com/r/rubygem/jekyll-octopod/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/jekyll-octopod.svg)](https://hub.docker.com/r/rubygem/jekyll-octopod/)
[![Gem Downloads](https://img.shields.io/gem/dt/jekyll-octopod.svg)](https://rubygems.org/gems/jekyll-octopod/)
# jekyll-octopod

Auto-Generated Docker image for jekyll-octopod to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/jekyll-octopod`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/jekyll-octopod`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/jekyll-octopod`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/jekyll-octopod/)
