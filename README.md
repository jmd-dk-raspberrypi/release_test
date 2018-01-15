## CO*N*CEPT
![renders](http://users-phys.au.dk/jmd/github/concept/concept_renders.gif)

CO*N*CEPT (**CO**smological ***N***-body **C**od**E** in **P**y**T**hon)
is a free and open-source code for cosmological structure formation.
The code should run on any Linux system, though it is primarily intended
for massively parallel computer clusters with distributed memory.
The code is written almost exclusively in Python, but achieves C-like
performance thanks to Cython.

### Version 0.1.0
The 0.1.0 release corresponds to the version of the code used for the
[νCO*N*CEPT paper](https://arxiv.org/abs/1712.03944).

### Quick installation instructions
As CO*N*CEPT has a lot of dependencies, it comes with an
[installation script](installer) which install all of these
(and CO*N*CEPT itself) into a single location.

The path to the CO*N*CEPT installation directory may be given
as an argument. If not, the installer will prompt you for a directory.

    ./installer /path/to/concept [--fast]
where the optional `--fast` option speeds up the installation by s


### Further documentation
Unfortunately, no up-to-date documentation exists.
An out-of-date [user guide](https://arxiv.org/abs/1510.07621) from back
when the code was particle-only,
as well as the [master's thesis](http://users-phys.au.dk/jmd/github/concept/masters_thesis.pdf)
for which CO*N*CEPT was originally written, are available.
