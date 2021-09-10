# Online-Multiplayer-Rock-Paper-Scissors
A game of rock,paper,scissors that can be played online over a network.

## Requirements
Run 
```
pip install -r requirements 
```
to install the required libraries.

## Usage

To run locally,
in separate terminals,
run

* `python3 server.py`
* `python3 client.py`
* `python3 client.py`

To run separately,
go to network.py and change the value of the variable `self.server` to the IP address of the machine hosting the server.
Then go to server.py and change the value of the variable `self.server` to the IP address of the machine hosting the server.
Then follow the steps as above.
