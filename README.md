

Installation steps:
need python3
git clone 
cd Reversehell

Setup process...

First we need to change the server ip address for our system ip address

**use to run nano server.py ---> change the ip address
After to change the client.py ip address client ip adderss is to give attacker ip address (it means what ip address to give server ip addres to give same ip address for client)

**use nano client.py ---> change the ip address

After first run the server file
use this command
* **python3 server.py

After run the client file
use this command
* **python3 client.py

***

//# How to Use

To use this reverse shell, two scripts need to be running

* **server.py** - runs on a public server and waits for clients to connect
* **client.py** - connects to a remote server and then wait for commands

***

## Server

To set up server script, simply run **server.py** using Python 3.4

`python3 server.py`

You will then enter an interactive prompt where you are able to view connected clients, select a specific client, and send commands to that client remotely.

To list all current connections:

`turtle> list`

To select a target from the list of clients:

`turtle> select 3`

***

## Client

In **client.py**, first change the IP address to that of the server and then run on target machine. If client does not have a compatible version of Python installed, you can create an executable by building from the source using **setup.py**.

`python setup.py build`
