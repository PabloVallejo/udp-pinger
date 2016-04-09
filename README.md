## UDP Pinger in Python

This is a simple [UDP](https://en.wikipedia.org/wiki/User_Datagram_Protocol) pinger excercise from the programming assignments of chapter two of [Computer Networking](http://www.amazon.com/Computer-Networking-Top-Down-Approach-Edition/dp/0132856204) book.

### Quick start

To get started, clone the repository and run the server code.

```bash
# Clone the repo.
$ git clone https://github.com/PabloVallejo/udp-pinger.git

# Cd in to repo.
$ cd udp-pinger

# Start the UDP server.
$ python server.py
```

Then, in a new terminal tab run the client code.

```bash

# Run client.
$ python client.py
```

**Sample output**
```bash
REQUEST TIMED OUT
TEST 1 0.00101709365845
TEST 2 0.000211000442505
REQUEST TIMED OUT
TEST 4 0.00022292137146
REQUEST TIMED OUT
REQUEST TIMED OUT
REQUEST TIMED OUT
TEST 8 0.00036096572876
TEST 9 0.000246047973633
```

### References

* [StackOverflow](https://stackoverflow.com/questions/27893804/udp-client-server-socket-in-python/27893987#27893987)
* [Smartedblog](https://smartedblog.wordpress.com/2013/05/02/networking-project-2-udp-pinger-program/)
* [Bedfordsarah](https://bedfordsarah.wordpress.com/2013/10/29/python-socket-programming-project-2-udp-pinger/)
