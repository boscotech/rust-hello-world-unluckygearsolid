# hello-world-rs
Make sure to read [Chapter 1 of Rust By Example](https://doc.rust-lang.org/rust-by-example/hello.html)! \
Use `git clone` to clone this repository. If you are using Windows, make sure to download git first via the [Git Bash Installer](https://github.com/git-for-windows/git/releases/download/v2.44.0.windows.1/Git-2.44.0-64-bit.exe).
```
git clone https://github.com/boscotech/rust-hello-world-YOUR_USERNAME
```
**Make sure to use your Github username everytime YOUR_USERNAME shows up.** <br />
Example:
```
git clone https://github.com/boscotech/rust-hello-world-lolpro11
```
Use `cd` to change into the directory.
```
cd rust-hello-world-YOUR_USERNAME
```
Now, install Rust. If you are using Windows, please install rust via the [Windows Rust Installer](https://static.rust-lang.org/rustup/dist/x86_64-pc-windows-msvc/rustup-init.exe).
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Next, `source` the Rust env. This runs the shell code inside the `env` file and allows you to use Rust.
```
source $HOME/.cargo/env
```
Finally, run the program by typing `cargo run`! You should see something like this.
```
Compiling helloworld v0.1.0 (/home/lolpro11/Documents/CS100RS/rust-hello-world-lolpro11)
    Finished dev [unoptimized + debuginfo] target(s) in 0.24s
     Running `target/debug/helloworld`
Hello, world!
```
To submit this assignment, run:
```
git add . # This adds all files in your working directory to the commit (your changes!)
git commit -m "finished assignment" # This logs your changes in a log. The -m adds a message in the log
git push # This "pushes" your changes to the remote server, thereby submitting your changes.
```
