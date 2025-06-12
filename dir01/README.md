# 2025-06-08

Venv: `~/.zvenv/011-2` 

```
$ sphinx-quickstart docs1
Welcome to the Sphinx 5.0.2 quickstart utility.

Please enter values for the following settings (just press Enter to
accept a default value, if one is given in brackets).

Selected root path: docs1

You have two options for placing the build directory for Sphinx output.
Either, you use a directory "_build" within the root path, or you separate
"source" and "build" directories within the root path.
> Separate source and build directories (y/n) [n]: n

The project name will occur in several places in the built documentation.
> Project name: Cd1
> Author name(s): SV
> Project release []: 1.0.1

If the documents are to be written in a language other than English,
you can select a language here by its language code. Sphinx will then
translate text that it generates into that language.

For a list of supported codes, see
https://www.sphinx-doc.org/en/master/usage/configuration.html#confval-language.
> Project language [en]: 

...

Finished: An initial directory structure has been created.

You should now populate your master file .../docs1/index.rst and create other documentation
source files. Use the Makefile to build the docs, like so:
   make builder
where "builder" is one of the supported builders, e.g. html, latex or linkcheck.
```


## Serving

`http.server` can also be invoked directly using the `-m` switch of the interpreter 
with a port number argument. Similar to the previous example, this serves files 
relative to the current directory:

```
python -m http.server 8000
```

By default, server binds itself to all interfaces. The option -b/--bind specifies 
a specific address to which it should bind. For example, the following command causes 
the server to bind to localhost only:

```
python -m http.server 8000 --bind 127.0.0.1
```

