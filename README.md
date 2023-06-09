# Encryption-and-Decryption1
Encryption is the process of converting plain, readable data into an unreadable format using an encryption algorithm and a secret key, ensuring confidentiality. Decryption is the reverse process, converting the encrypted data back into its original form using the same key, enabling authorized individuals to access the information securely.
1.ALTGRAPH :
altgraph is a fork of graphlib: a graph (network) package for constructing graphs, BFS and DFS traversals, topological sort, shortest paths, etc. with graphviz output. 
The primary users of this package are macholib and modulegraph. 
2.CERTIFI :
Certifi provides Mozilla’s carefully curated collection of Root Certificates for validating the trustworthiness of SSL certificates while verifying the identity of TLS hosts. It has been extracted from the Requests project.
3.	CFFI :
 CFFI is a Python module which will read C function prototypes automatically generate some of the marshalling to and from these C functions. 
CFFI can be used in one of four modes: ‘ABI’ versus ‘API’ level, each with ‘in-line’ or ‘out-of-line’ preparation (or compilation). 
4.	CHARDET :
Chardet: The Universal Character Encoding Detector.Character encoding auto-detection in Python. As smart as your browser. Open source. 
5.	CRYPTOGRAPHY :
Python supports a cryptography package that helps us encrypt and decrypt data. The fernet module of the cryptography package has inbuilt functions for the generation of the key, encryption of plaintext into ciphertext, and decryption of ciphertext into plaintext using the encrypt and decrypt methods respectively. 
6.	DOCOPT :
Docopt is a command line interface description module. It helps you define a interface for a command-line application and generates parser for it. The interface message in docopt is a formalized help message. 
You can install docopt module in various ways, pip is one of the best ways to install docopt. 
7.FUTURE :
    The purpose of this package is to provide a lightweight and unified Future API for sequential and parallel processing of R expression via futures.This package implements sequential, multicore, multisession, and cluster futures. 
8.IDNA :
      Support for the Internationalised Domain Names in Applications (IDNA) protocol as specified in RFC 5891. This is the latest version of the protocol and is sometimes referred to as “IDNA 2008”. 
9.PEFILE :
pefile is a multi-platform Python module to parse and work with Portable Executable (PE) files. Most of the information contained in the PE file headers is accessible, as well as all the sections' details and data. 
10.PYCPARSER :
pycparser is a parser for the C language, written in pure Python. It is a module designed to be easily integrated into applications that need to parse C source code. 
11.PYINSTALLER :
PyInstaller is a Python package, installed with pip ( pip install pyinstaller ). PyInstaller can be installed in your default Python installation, but it's best to create a virtual environment for the project you want to package and install PyInstaller there. 
12.PYINSTALLER-HOOKS-CONTRIB :
A "hook" file extends PyInstaller to adapt it to the special needs and methods used by a Python package. The word "hook" is used for two kinds of files. A runtime hook helps the bootloader to launch an app, setting up the environment. 
13.PYWIN32-CTYPE :
Pywin32 is basically a very thin wrapper of python that allows us to interact with COM objects and automate Windows applications with python. The power of this approach is that you can pretty much do anything that a Microsoft Application can do through python. 
14. REQUESTS :
Python requests module has several built-in methods to make Http requests to specified URI using GET, POST, PUT, PATCH or HEAD requests. A Http request is meant to either retrieve data from a specified URI or to push data to a server. It works as a requestresponse protocol between a client and a server. 
15 .STDIOMASK : 
     A cross-platform Python module for entering passwords to a stdio terminal and displaying a ** mask, which getpass cannot do. 
16.TK  :
     The tkinter package (“Tk interface”) is the standard Python interface to the Tcl/Tk GUI toolkit. Both Tk and tkinter are available on most Unix platforms, including macOS, as well as on Windows systems. 
17.TQDM :
Tqdm is a library in Python which is used for creating Progress Meters or Progress Bars. tqdm got its name from the Arabic name taqaddum which means ‘progress’.Implementingtqdm can be done effortlessly in our loops, functions. 
18.URLLIB3 :
     The urllib3 module is a powerful, sanity-friendly HTTP client for 
Python. It supports thread safety, connection pooling, client-side SSL/TLS verification, file uploads with multipart encoding, helpers for retrying requests and dealing with HTTP redirects, gzip and deflate encoding, and proxy for HTTP and SOCKS. 
19. WINCERTSTORE :
     Python module to extract CA and CRL certs from Windows' cert store (ctypes based). Project description Warning The package is deprecated. Since Python 2.7.9 ssl.create_default_context () automatically loads certificates from Windows’ cert store. wincertstore provides an interface to access Windows’ CA and CRL 
certificates. 

20.YARG :
Yargs module is used for creating your own command-line commands in node.js and helps in generating an elegant user interface. This module makes command-line arguments flexible and easy to use. 

STEPS TO IMPLEMENT :
Step:1 Run the program .
Step:2 GUI for encryption and decryption will be opened.
Step:3 Type the password as 1234,and give (salt)i.e password givento encrypt or decrypt a particular file(it can be a number or a specialcharacters )
Step:4 Browse and select a file or folder that you want to encrypt.
Step:5 This step lets you know whether you file or folder is selectedor not.

Step:6 Click on encrypt,as shown below a message box appearssaying"All files are encrypted".
Step:7 Hence,the data is encrypted
Step:8 Again give the password and salt(the one which is given forencryption)and browse the file that you encrypted in the previousscenario and click on decrypt.
Step:9 Now you can see that your encrypted data is decrypted and hascome to its original form.
Further we can encrypt files such as .txt , .docs , .jpeg , .png etc.....
