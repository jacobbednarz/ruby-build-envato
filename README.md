# Envato Ruby

Custom `ruby-build` definition for installing various versions of Ruby used at
Envato.

### Definitions

- **Debug**: If a version includes `debug` in the name it is a version with
  debugging options, CFLAGS, etc. enabled. This is not recommended for full time
  production use.

### Downloading

```
$ git clone https://github.com/jacobbednarz/ruby-build-envato.git "$(rbenv root)/plugins/ruby-build-envato"
```

### Installation

```
$ rbenv install <DEFINITION>
```

To see all the available versions:

```
$ rbenv install --list | grep envato
```
