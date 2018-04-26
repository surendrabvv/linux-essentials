## alias

### Using alias, frequently used commands can be invoked / executed by assigning commands to a simple user defined keyword

#### Example

We usually use **ssh** to login to the remote servers from any unix / linux machine. Example command will be like as follows,

```sh
$ ssh username@remotehostenvironment.com
```

Everytime typing the above command will be little difficult as we need to remember username and hostname also. But, if we add a simple alias command for this. Then, just we need to remember that keyword.

Here is how to add an **alias** command,

* Check whether `.bashrc` or `.bash_profile` file is present in your home directory or not. If not, create either one of these.
* Then add following line to either one of above files.

```sh
$ alias remote-host="ssh username@remotehostenvironment.com"
```
* Now, open the terminal and type the following command.

```sh
$ remote-host
```
* Above command will output the same result of `ssh username@remotehostenvironment.com` command.
