### Welcome to go-hep.

`go-hep` is a set of libraries and applications allowing High Energy Physicists to write efficient analysis code in the [Go](https://golang.org) programming language.

[Go](https://golang.org) brings the fast edit-compile-run cycle that interpreted language users know and the runtime efficiency that compiled languages users expect.
[go-hep](http://go-hep.github.io) provides the needed `HEP` oriented packages on top of this concurrency-enabled language.
 
`go-hep` currently sports the following packages:
- [go-hep/fads](https://github.com/go-hep/fads): a fast detector simulation toolkit
- [go-hep/fastjet](https://github.com/go-hep/fastjet): a jet clustering algorithms package (WIP)
- [go-hep/fmom](https://github.com/go-hep/fmom): a 4-vectors library
- [go-hep/fwk](https://github.com/go-hep/fwk): a concurrency-enabled framework
- [go-hep/hbook](https://github.com/go-hep/hbook): histograms and n-tuples (WIP)
- [go-hep/hplot](https://github.com/go-hep/hplot): interactive plotting (WIP)
- [go-hep/hepmc](https://github.com/go-hep/hepmc): `HepMC` in pure [Go](https://golang.org) (EDM + I/O)
- [go-hep/hepevt](https://github.com/go-hep/hepevt): `HEPEVT` bindings
- [go-hep/heppdt](https://github.com/go-hep/heppdt): `HEP` particle data table
- [go-hep/lhef](https://github.com/go-hep/lhef): Les Houches Event File format
- [go-hep/croot](https://github.com/go-hep/croot): bindings to a subset of [ROOT](https://root.cern.ch) I/O
- [go-hep/rio](https://github.com/go-hep/rio): `go-hep` record oriented I/O
- [go-hep/sio](https://github.com/go-hep/sio): `LCIO` I/O
- [go-hep/slha](https://github.com/go-hep/slha): `SUSY` Les Houches Accord I/O

### Installation

`go-hep` packages are installable via the `go get` command:

```sh
$ go get github.com/go-hep/fads
```

Just select the package you are interested in and `go get` will take care of fetching, building and installing it, as well as its dependencies, recursively.

`go-hep` is available on all [Go](https://golang.org) supported platforms:
- `linux-{amd64,386,arm}`
- `darwin-{amd64,386}`
- `windows-{amd64,386}`
- `freebsd-{amd64,386,arm}`

### License
All `go-hep` code is released under a [BSD-3 license](https://github.com/go-hep/license).

### Authors and Contributors
``go-hep`` was primarily written by Sebastien Binet (@sbinet).
The complete AUTHORS and CONTRIBUTORS list can be consulted on the dedicated [license](https://github.com/go-hep/license) repository.

### Support or Contact
Having trouble with ``go-hep``?  
Check out the [documentation](https://github.com/go-hep/tutos) or contact us at go-hep@googlegroups.com and we’ll help you sort it out.
