# www.alexhilson.co.uk

Personal site/blog, themed using [Hyde](https://github.com/poole/hyde).

## Building

I use the [grahamc/jekyll](https://github.com/grahamc/docker-jekyll) Docker image to provide Jekyll, and Vagrant to provide the development environment.

    vagrant up
    vagrant ssh
    cd /vagrant
    jekyll build

To use the jekyll server a couple of extra options are needed:

    jekyll serve -H 0.0.0.0 --force_polling
