# hello-world-rs
Use `git clone` to clone this repository.
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
Now, install Rust.
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
