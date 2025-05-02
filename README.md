# tracell

**A tiny package install tracer for macOS.**  
Because `porg` doesn't work here, and I still want to know what `make install` did.

---

`tracell` is a minimalist toolset for tracking files installed into your `${HOME}/local`.  
It takes before/after snapshots of your prefix directory and logs what changed.  
Perfect for those who like to build things by hand but still want a clean uninstall.

Inspired by the spirit of [Linux From Scratch](https://www.linuxfromscratch.org/) and tools like `porg`, `pkgsrc`, and the UNIX tradition of doing one thing well.

## Usage

```sh
% tracell-install foo make install
```

## License

[WTFPL version 2](http://www.wtfpl.net/)

## Author

sasairc (https://github.com/sasairc2)
