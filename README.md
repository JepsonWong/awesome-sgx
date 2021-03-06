# awesome-sgx

Collection of material for learning SGX.

## Table of Contents

- [SDK](##SDK)
- [Security](##Security)
- [Paper](##Paper)
- [GAME](##GAME)
- [EMULATOR](##emulator)
- [LibOS](##LibOS)
- [DOCKER](##DOCKER)
- [CRYPTO](##CRYPTO)
- [NETWORK](##NETWORK)
- [DATABASE](##DATABASE)
- [Programming Language](##ProgrammingLanguage)
- [Tool&&DEBUG](##Tool&&DEBUG)
- [BlockChain](##BlockChain)

## SDK

* [01org/linux-sgx](https://github.com/01org/linux-sgx) - Intel(R) Software Guard Extensions for Linux* OS [<img src="https://api.travis-ci.org/01org/linux-sgx.svg?branch=master">](https://travis-ci.org/01org/linux-sgx)
* [baidu/rust-sgx-sdk](https://github.com/baidu/rust-sgx-sdk) - Rust SGX SDK provides the ability to write Intel SGX applications in Rust Programming Language. [<img src="https://api.travis-ci.org/baidu/rust-sgx-sdk.svg?branch=master">](https://travis-ci.org/baidu/rust-sgx-sdk)
* [adombeck/python-sgx](https://github.com/adombeck/python-sgx) - Python interface to the SGX SDK.

## Security

* [lsds/spectre-attack-sgx](https://github.com/lsds/spectre-attack-sgx) - Spectre attack against SGX enclave.
* [bl4ck5un/mbedtls-SGX](https://github.com/bl4ck5un/mbedtls-SGX) - mbedtls-SGX: a SGX-friendly TLS stack (ported from mbedtls).
* [jaebaek/SGX-Shield](https://github.com/jaebaek/SGX-Shield) - SGX-Shield: Enabling Address Space Layout Randomization (ASLR) for SGX Programs.
* [tudinfse/sgxbounds](https://github.com/tudinfse/sgxbounds) - SGXBounds: Memory Safety for Shielded Execution (compiler pass and runtime).

## Paper

* [vschiavoni/sgx-papers](https://github.com/vschiavoni/sgx-papers) - A list of system papers using/about Intel SGX.

## GAME

* [utds3lab/sgx-biniax2](https://github.com/utds3lab/sgx-biniax2) - A Linux game with SGX [<img src="https://api.travis-ci.org/utds3lab/sgx-biniax2.svg?branch=master">](https://travis-ci.org/utds3lab/sgx-biniax2)
* [djwessel/sgx-snake](https://github.com/djwessel/sgx-snake) - A simple snake game implemented with SGX.
* [suinkang/SGX-Doom3](https://github.com/suinkang/SGX-Doom3) - Doom3 with SGX.

## EMULATOR

* [tristartom/sgx-emulator](https://github.com/tristartom/sgx-emulator) - An Emulator and SDK for Intel SGX extension [<img src="https://api.travis-ci.org/tristartom/sgx-emulator.svg?branch=master">](https://travis-ci.org/tristartom/sgx-emulator)
* [intel/qemu-sgx](https://github.com/intel/qemu-sgx) - qemu with SGX [<img src="https://api.travis-ci.org/intel/qemu-sgx.svg?branch=master">](https://travis-ci.org/intel/qemu-sgx)
* [sslab-gatech/opensgx](https://github.com/sslab-gatech/opensgx) - OpenSGX: An open platform for Intel SGX [<img src="https://api.travis-ci.org/sslab-gatech/opensgx.svg?branch=master">](https://travis-ci.org/sslab-gatech/opensgx)

## LibOS

* [oscarlab/graphene](https://github.com/oscarlab/graphene) - Graphene / Graphene-SGX Library OS - a library OS for Linux multi-process applications, with Intel SGX support https://github.com/oscarlab/graphene/… [<img src="https://api.travis-ci.org/oscarlab/graphene.svg?branch=master">](https://travis-ci.org/oscarlab/graphene)
* [SCONE](https://www.usenix.org/system/files/conference/osdi16/osdi16-arnautov.pdf) - SCONE: Secure Linux Containers with Intel SGX
* [SGXKernel](http://delivery.acm.org/10.1145/3080000/3075572/p35-Tian.pdf?ip=113.240.234.248&id=3075572&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2E1C775F1AC6329F5A%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&CFID=1000423527&CFTOKEN=74748264&__acm__=1509418666_8d60f199060353b9d2e3a828901a729e) - SGXKernel: A Library Operating System Optimized for Intel SGX
* [Haven](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-baumann.pdf) - Shielding Applications from an Untrusted Cloud with Haven.
* [shwetasshinde24/Panoply](https://github.com/shwetasshinde24/Panoply) - Low-TCB Linux Applications with SGX Enclaves.

## DOCKER

* [tozd/docker-sgx](https://github.com/tozd/docker-sgx) - A Docker image with Intel SGX support. https://hub.docker.com/r/tozd/sgx/ [<img src="https://api.travis-ci.org/tozd/docker-sgx.svg?branch=master">](https://travis-ci.org/tozd/docker-sgx)

## CRYPTO

* [intel/intel-sgx-ssl](https://github.com/intel/intel-sgx-ssl) - Intel® Software Guard Extensions SSL.
* [WolfSSL](https://github.com/NickolasLapp/linux_sgx) - WolfSSL with SGX for Linux OS using Eclipse IDE and SGX Plugin.
* [momalab/SGXCrypter](https://github.com/momalab/SGXCrypter) - SGXCrypter is a novel approach on encryption based binary packing. [<img src="https://api.travis-ci.org/momalab/SGXCrypter.svg?branch=master">](https://travis-ci.org/momalab/SGXCrypter)
* [rscosta/SGXCryptoFile](https://github.com/rscosta/SGXCryptoFile) - SgxCryptoFile - App for Encrypting and Decrypting Files using Intel SGX.[<img src="https://api.travis-ci.org/rscosta/SGXCryptoFile.svg?branch=master">](https://travis-ci.org/rscosta/SGXCryptoFile)
* [oweisse/sgx_crypto_wrapper](https://github.com/oweisse/sgx_crypto_wrapper) - A Python wrapper for sgx_tlibcrypto library.[<img src="https://api.travis-ci.org/oweisse/sgx_crypto_wrapper.svg?branch=master">](https://travis-ci.org/oweisse/sgx_crypto_wrapper)
* [sparkly9399/SGX-OpenSSL](https://github.com/sparkly9399/SGX-OpenSSL) - OpenSSL library for SGX application.
* [ayeks/TresorSGX](https://github.com/ayeks/TresorSGX) - Securing storage encryption by using Intel SGX enclaves. First attempt for the isolation of OS components with trusted enclaves.
* [kudelskisecurity/sgx-reencrypt](https://github.com/kudelskisecurity/sgx-reencrypt) - PoC of an SGX enclave performing symmetric reencryption.

## NETWORK

* [kaist-ina/SGX-Tor](https://github.com/kaist-ina/SGX-Tor) - https://github.com/kaist-ina/SGX-Tor
* [jnferguson/pwd](https://github.com/jnferguson/pwd) - SGX password storage / authentication subsystem.

## DATABASE

* [yerzhan7/SGX_SQLite](https://github.com/yerzhan7/SGX_SQLite) - SQLite database inside a secure Intel SGX enclave (Linux). [<img src="https://api.travis-ci.org/yerzhan7/SGX_SQLite.svg?branch=master">](https://travis-ci.org/yerzhan7/SGX_SQLite)


## ProgrammingLanguage

* [C#](https://github.com/Liaojinghui/A_C-Sharp_Project_With_SGX) - A C# example project downloaded from intel with GUI implemented with SGX
* [GO](https://github.com/rupc/go-with-intel-sgx) - Intel SGX with GoLang
* [Python](https://github.com/adombeck/python-sgx) - Python interface to the SGX SDK.
* [JAVA](https://github.com/sm67nono/Intel_SGX_Proj) - Trusted Computing Base with Intel SGX and Java JNI.
* [lishen-nt/sgx-language-adapter](https://github.com/lishen-nt/sgx-language-adapter) - SGX language adapter for java and python.

## Tool&&DEBUG

* [jovanbulck/sgx-step](https://github.com/jovanbulck/sgx-step) - A practical attack framework for precise enclave execution control. [<img src="https://api.travis-ci.org/jovanbulck/sgx-step.svg?branch=master">](https://travis-ci.org/jovanbulck/sgx-step)
* [swarupchandra/secure-analytics-sgx](https://github.com/swarupchandra/secure-analytics-sgx) - Securing Data Analytics on Intel SGX using Randomization.
* [Glamdring](https://www.usenix.org/system/files/conference/atc17/atc17-lind.pdf) - Glamdring: Automatic Application Partitioning for Intel SGX.
* [kudelskisecurity/sgxfun](https://github.com/kudelskisecurity/sgxfun) - SGX command-line tools and paper.
* [ireed/SGX](https://github.com/ireed/SGX) - Code samples and tutorials for using intel software guard extensions.
* [jethrogb/sgx-utils](https://github.com/jethrogb/sgx-utils) - Various utilities for Intel SGX hardware.

## BlockChain

* [LedgerHQ/bolos-enclave](https://github.com/LedgerHQ/bolos-enclave)
* [luckychain/lucky](https://github.com/luckychain/lucky) - Proof of luck Intel SGX and IPFS based blockchain.
* [Town Crier](https://github.com/bl4ck5un/Town-Crier) - Town Crier: an Authenticated Data Feeds for Smart Contracts http://town-crier.org