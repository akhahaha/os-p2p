OS P2P
===================
	UCLA CS 111 Lab 4
	Professor Peter Reiher
	Winter 2014

	Alan Kha		904030522	akhahaha@gmail.com.com
-------------------------------------------------------------------------------
Summary
---------------
Implements a peer-to-peer communication network with tracker and peer nodes.

Features
---------------
 - Fixed buffer overflow vulnerabilities.
 - Limited upload access.
 - MD5 file integrity verification.
 - DOS resistant (prevents immediate same peer repeat request).
 - Evil mode 1: Attempts filename buffer overflow attack.
 - Evil mode 2: Attempts DOS attack flooding peers with repeat file requests.
 - Evil mode 3: Attempts disk overrun attack by endlessly uploading data.

Installation
---------------
1. Extract into CS 111 Ubuntu distribution.
2. Run in QEMU emulator with ./run-good.

Limitations
---------------
