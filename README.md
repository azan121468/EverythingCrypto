# Hello there!

In this repository I collect my adventures in the Cryptography world.
You will find
- Medium-Highly Detailed explanations of algorithms
- Implementations in Python / Sage
- Common libraries for solving the problems
- Everything is full of resources (from Youtube videos with intuitive explanations to detailed papers on the subject)

# IMPORTANT NOTE
I **HIGHLY** recommend using nbviewer if you're reading these online: https://nbviewer.jupyter.org/github/zademn/EverythingCrypto/tree/master/  
- Github doesn't render the all mathematics inside the notebooks
- Github doesn't render images properly inside the notebooks 

## Disclaimer
- This whole repository is for educational purposes
- DO NOT USE ANY OF THE ALGORITHMS IN REAL WORLD APPLICATIONS


# Structure?

## Notebooks
- For educational and "ease to follow" purposes I decided to work in notebooks. Notebook are structured as follows:
    - Prerequisites = list of subjects/notebooks that you need to cover before attempting the subject
    - Theory = Mathematical explanation + intuitions
    - Code = Python,Sage or other library
    - Resources = List of resources for further reading
 ## PDF's
- Some basic theory in the form of pdf's here and there
    
## Directories

Directories are organized by categories
- Security theory 
    - Basic definitions and what to expect (Start with this)
- Secret sharing schemes
    - General Idea and SSSS


- Mathematics = Here you will find the basic structures(groups, curves, etc) and algorithms that I studied
    - Number theory - Start with this
    - Elliptic Curves - Theory
    - Discrete Logarithm Problem 
    - Elliptic Curve Discrete Logarithm Problem 
    - Factorizations 
    - Lattices
    - Primes and primality tests

- Public Key = Each cryptosystem will have an introduction and a folder with vulnerabilities (NOTE: mathematical vulnerabilities (Ex: factorizations, dlp) will not be covered to avoid monotony. I assume you can connect the dots) 
    - RSA + vulnerabilities
    - Diffie Hellman + vulnerabilities
    - Elgamal
- Digital signatures
    - ECDSA + vulnerabilities
    - RSADSA + vulnerabilities

- PRNG's
    - Pseudorandom generators, pseudorandom functions, 
    - Implementations: chacha20, LFSRs, Geffe (Correlation attack)
- Block Ciphers
    - AES, DES
    - Block ciphers modes of operation - pdf
- Message Integrity
    - MACs and hashes theory - pdf
    - Constructions - Merkle damgard and sponge
    - Length Extension attack
    - HMAC
- Authenticated Encryption
    - AE and AEAD - pdf
    - GCM and the the forbidden attack
    
Each directory will have a README.md that will contain the difficulty MY difficulty ranking of different subjects, attacks etc.

# How to tackle this repository?
Whatever fits your needs (Start with the security theory folder though to know what to expect)
1. Follow along with a book (There is a book directory)
2. Depth-first fashion (for people that have good foundations):
    - Pick a bigger subject
    - Study it thoroughly (from the lowest difficulty to the highest)
3. Breadth-first fashion (for starters):
    - Go through every topic at the lowest difficulty
    - Raise the difficulty and start again
4. My Take
- Security theory dir -> Symmetric / Public 
- Symmetric encryption
    - PRGNG -> Block ciphers -> Message Integrity -> Authenticated Encryption
- Public Encryption
    - Maths/Number Theory -> Public Key Encryption -> Digital Signatures
    - Maths when needed

# TODO
Not necessarily in this order   
(As of 26 Dec 2020)
- [ ] SIS, LWE
- [x] Hashes - 26 dec
- [ ] Code for DES and Feistel ciphers
- [ ] Lattice theory + LLL details and implementation
- [ ] Lattice Cryptosystems
- [ ] Homomorphic encryption
- [ ] Public key theory
