# SHA-256-Python-Implementation
Implementation of SHA-256 (Secure Hashing Algorithm) in pure python.

To clone this repository enter the following command in your terminal.

    $ git clone https://github.com/Studiex/SHA-256-Python-Implementation.git

## Usage

    usage: sha256.py [-h] [-s INPUT_STRING] [-f INPUT_FILE]
    
    optional arguments:
      -h, --help            show this help message and exit
      -s INPUT_STRING, --string INPUT_STRING
                            Hash the string
      -f INPUT_FILE, --file INPUT_FILE
                            Hash contents of a file

## Examples

    $ .\sha256.py --string "Hello World"
    a591a6d40bf420404a011733cfb7b190d62c65bf0bcda32b57b277d9ad9f146e
   
    $ .\sha256.py -s "Python"
    18885f27b5af9012df19e496460f9294d5ab76128824c6f993787004f6d9a7db
    
    $ .\sha256.py --file .\hello_world.txt
    a0d77b70752c5b9fb2f6788a4e0ace8a0a8e0be3d1f4c7f9883afdaabedb5b20
    
    $ .\sha256.py -f .\hello_world.txt
    a0d77b70752c5b9fb2f6788a4e0ace8a0a8e0be3d1f4c7f9883afdaabedb5b20

## References
Get a detailed understanding of the algorithm from the following websites.

Pseudocode: https://en.wikipedia.org/wiki/SHA-2

Step-by-step explanation: https://qvault.io/cryptography/how-sha-2-works-step-by-step-sha-256/
