# pyircfuzz

This is a fuzzer for IRC clients written in Python 3. Hence it shall be called pyircfuzz.

## Getting Started

Run ircfuzz.py. Run your IRC client. Connect to localhost port 6667 with your IRC client. Wait for IRC client to crash. See log in ircfuzz.log. Try to use log to reproduce crash.

If you have something in ircfuzz.log that you would like to save, copy it to some other filename before running ircfuzz.py again, because ircfuzz.py will overwrite it.

### Prerequisites

* A recent version of Python 3
* An IRC client that you intend to fuzz
* Patience

### Installing

No need to install pyircfuzz.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
