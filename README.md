wamr for Unikraft
=============================

This is the port of wamr for Unikraft as external library. If given
the --repl parameter this port will run REPL mode. Alternatively you
can run a program from a file if passed as a initrd parameter. For
example, if using KVM/QEMU:

* REPL: add -append "--repl" to the command line
* initrd: add -initrd <filename.wasm> to the command line

If you don't want or need your application to provide a main, you can
check the "Provide main function" option in the wamr menu and this
library will provide one for you.

Please refer to the `README.md` as well as the documentation in the `doc/`
subdirectory of the main unikraft repository.
