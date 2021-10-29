# OpenSSL Test

## Index

  - [Overview](#overview) 
  - [Getting Started](#getting-started)

## Overview

- In this project, several cryptos of openssl are tested.
  - Random
  - AES
  - RSAES
  - HAMC
- In addition, a **hybrid cryptosystem protocol** was implemented using the OpenSSL function, and a **simple chat program** was implemented using that protocol.

## Getting Started

### Dependencies

- OpenSSL install

  ```
  ## 
  cd openssl-test
  wget https://github.com/openssl/openssl/archive/refs/tags/OpenSSL_1_1_1l.tar.gz
  tar -zvxf OpenSSL_1_1_1l.tar.gz
  
  rm OpenSSL_1_1_1l.tar.gz && mv openssl-OpenSSL_1_1_1l openssl
  cd openssl
  
  ## build & install
  ./config
  make
  make test
  sudo make install
  ```
