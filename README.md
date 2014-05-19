# inside-out-outside-in

This is an installer for a project designed to support a Java programming workshop that explores the differences between inside-out and outside-in design approaches in software development. 

## Steps

The instructions assume you are beginning with a virtual machine provisioned with https://github.com/neopragma/provision-java-dev-training-vm (or a functionally equivalent configuration arrived at by other means). 

### Step 1 - Clone this repo

```shell
cd
git clone https://github.com/neopragma-training/inside-out-outside-in
```

### Step 2 - Run the setup script

Run the setup script.

```shell
cd ~/inside-out-outside-in
./setup
```

### Step 3 - Verify the setup

The last thing the setup script does is to run a script named verify. Check the output from verify and see if any of the installation steps failed. If so, investigate and resolve the problems. If you discover a problem with the setup script, fix it and make a pull request.

## After installation

If the setup script is successful, you will have the following:

* Java JEE 1.7 JDK
* Eclipse IDE
* ArgoUML diagramming tool
* Documentation about the programming workshop
