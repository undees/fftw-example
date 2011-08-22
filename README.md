This example provides an extremely simple demonstration of
[FFTW][fftw], the Fastest Fourier Transform in the West.  To run the
example, you'll need to install FFTW based on the instructions on the
site.  If you're on a Mac and have [Homebrew][brew] installed, you
can just type:

```
brew install fftw
```

Compilation instructions vary by platform.  On the Mac and other
UNIX-like systems, you should just be able to type:

```
g++ -lfftw3 fftw_example.c
```

Enjoy!

[fftw]: http://www.fftw.org
[brew]: http://mxcl.github.com/homebrew
