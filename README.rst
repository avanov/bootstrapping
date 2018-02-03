=============
Bootstrapping
=============

A set of reminders of environment bootstrapping


OSX
===

Rust
----

..code-block:: bash

    curl https://sh.rustup.rs -sSf | sh

    . ~/.cargo/env

    rustup update


* Read https://doc.rust-lang.org/book/second-edition/ch01-02-hello-world.html
* Use playground for trying doc examples https://play.rust-lang.org/
* Use stdlib reference for getting details about data types https://doc.rust-lang.org/std/


..code-block:: bash

    cargo new myapp --bin && cd myapp

    cargo run

    cargo run --release


Haskell
-------

..code-block:: bash

    $ brew install haskell-stack


* Read https://www.yesodweb.com/page/quickstart
