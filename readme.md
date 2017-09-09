A piece of interactive fiction written using [twee2](https://dan-q.github.io/twee2/) and [snowman](https://github.com/klembot/snowman).

## Installation

To compile, ensure you have a version of [Ruby](https://www.ruby-lang.org/en/downloads/) later than 2.1.6 (e.g. `apt-get install ruby ruby-dev` on Ubuntu). Then, run 

```
gem install twee2
```

To build the story run

```
twee2 build tunnel.tw2 tunnel.html
```

and for live recompilation run

```
twee2 watch tunnel.tw2 tunnel.html
```
