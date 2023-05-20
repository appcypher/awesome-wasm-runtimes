# Awesome WebAssembly Runtimes ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

This repo contains a list of virtual machines and tools that execute the WebAssembly(wasm) format and/or compile it to executable machine code :octocat:

#### Legend
:rocket: - Active development</br>
:sleeping: - Unmaintained (been more than a year since last commit)</br>

## CONTENTS

- [aWsm](#awsm) <sup><sup>:rocket:</sup></sup></br>
- [CMM of Wasm](#cmm) <sup><sup>:sleeping:</sup></sup></br>
- [EOSVM](#eosvm) <sup><sup>:rocket:</sup></sup></br>
- [FDVM](#fdvm) <sup><sup>:sleeping:</sup></sup></br>
- [Fizzy](#fizzy) <sup><sup>:rocket:</sup></sup></br>
- [GraalWASM](#graalwasm) <sup><sup>:rocket:</sup></sup></br>
- [Happy New Moon With Report](#happy-new-moon-with-report) <sup><sup>:rocket:</sup></sup></br>
- [inNative](#innative) <sup><sup>:rocket:</sup></sup></br>
- [Life](#life) <sup><sup>:sleeping:</sup></sup></br>
- [Lucet](#lucet) <sup><sup>:rocket:</sup></sup></br>
- [wasm3](#wasm3) <sup><sup>:rocket:</sup></sup></br>
- [Motor](#motor) <sup><sup>:sleeping:</sup></sup></br>
- [py-wasm](#py-wasm) <sup><sup>:sleeping:</sup></sup></br>
- [Serverless Wasm](#serverless-wasm) <sup><sup>:sleeping:</sup></sup></br>
- [Swam](#swam) <sup><sup>:rocket:</sup></sup></br>
- [VMIR](#vmir) <sup><sup>:sleeping:</sup></sup></br>
- [wac](#wac) <sup><sup>:sleeping:</sup></sup></br>
- [Wagon](#wagon) <sup><sup>:sleeping:</sup></sup></br>
- [WAKit](#wakit) <sup><sup>:rocket:</sup></sup></br>
- [Warpy](#warpy) <sup><sup>:sleeping:</sup></sup></br>
- [WasmEdge](#wasmedge) <sup><sup>:rocket:</sup></sup></br>
- [Wasmer](#wasmer) <sup><sup>:rocket:</sup></sup></br>
- [Wasmi](#wasmi) <sup><sup>:rocket:</sup></sup></br>
- [Wasmo](#wasmo) <sup><sup>:rocket:</sup></sup></br>
- [WasmRT](#wasmrt) <sup><sup>:sleeping:</sup></sup></br>
- [Wasmtime](#wasmtime) <sup><sup>:rocket:</sup></sup></br>
- [WasmVM](#wasmvm1) <sup><sup>:rocket:</sup></sup></br>
- [WasmVM](#wasmvm2) <sup><sup>:sleeping:</sup></sup></br>
- [WAVM](#wavm) <sup><sup>:rocket:</sup></sup></br>
- [WebAssembly](#webassembly) <sup><sup>:sleeping:</sup></sup></br>
- [WebAssembly Micro Runtime](#wamr) <sup><sup>:rocket:</sup></sup></br>
- [TWVM](#twvm) <sup><sup>:rocket:</sup></sup></br>
- [wazero](#wazero) <sup><sup>:rocket:</sup></sup></br>

----------------


## <a name="awsm"></a>[aWsm](https://github.com/gwsystems/aWsm) <sup>[top⇈](#contents)</sup>

> aWsm is a compiler and runtime for compiling WebAssembly (Wasm) code into llvm bytecode, then into sandboxed binaries you can run on various platforms.

* **Languages written in**

    <table>
    <tr>
        <td>Rust</td>
        <td>C</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>AOT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    <table>
    <tr>
        <td>C</td>
    </tr>
    </table>

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
    </tr>
    </table>


## <a name="cmm"></a>[CMM of Wasm](https://github.com/SimonJF/cmm_of_wasm) <sup>[top⇈](#contents)</sup>
> A compiler from WebAssembly to native code, via the OCaml backend.

* **Languages written in**

    <table>
    <tr>
        <td>OCaml</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>OCaml Compiler</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>AOT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
    </tr>
    </table>

## <a name="eosvm"></a>[EOSVM](https://github.com/EOSIO/eos-vm) <sup>[top⇈](#contents)</sup>
> EOS VM is designed from the ground up for the high demands of blockchain applications which require far more from a WebAssembly engine than those designed for web browsers or standards development.

* **Languages written in**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="fdvm"></a>[FDVM](https://github.com/funcdef/fdvm) <sup>[top⇈](#contents)</sup>
> WASM runtime to develop server-side WebAssembly applications.

* **Languages written in**

    <table>
    <tr>
        <td>JavaScript</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>NodeJS(V8)</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="fizzy"></a>[Fizzy](https://github.com/wasmx/fizzy) <sup>[top⇈](#contents)</sup>
> Fizzy aims to be a fast, deterministic, and pedantic WebAssembly interpreter written in C++.

* **Languages written in**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **Compiler framework**

    - `N/A`

* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreter</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **Non-web standards**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
    </tr>
    </table>

## <a name="graalwasm"></a>[GraalWasm](https://github.com/oracle/graal/tree/master/wasm) <sup>[top⇈](#contents)</sup>
GraalWasm is a WebAssembly engine implemented in the GraalVM. It can interpret and compile WebAssembly programs in the binary format, or be embedded into other programs.

* **Languages written in**

    <table>
    <tr>
        <td>Java</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>GraalVM</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    <table>
    <tr>
        <td>Java</td>
        <td>JVM</td>
        <td>Graal supported languages</td>
    </tr>
    </table>

* **Non-MVP features supported**

    <table>
    <tr>
    </tr>
    </table>

* **Host APIs supported**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **Non-web standards**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **Used by**

    - [GraalVM JavaScript](https://github.com/graalvm/graaljs) - A high performance implementation of the JavaScript programming language.

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="happy-new-moon-with-report"></a>[Happy New Moon With Report](https://github.com/fishjd/HappyNewMoonWithReport) <sup>[top⇈](#contents)</sup>

Happy New Moon with Report is an open-source implementation of WebAssembly written entirely in Java. It is used to run or test Web Assembly Modules (*.wasm) in Java.

* **Languages written in**

    <table>
    <tr>
        <td>Java</td>
    </tr>
    </table>

* **Compiler framework**

    - `N/A`

* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    <table>
    <tr>
        <td>Java</td>
        <td>JVM languages</td>
    </tr>
    </table>

* **Non-MVP features supported**

    <table>
    <tr>
    	<td>Sign Extensions</td>
    </tr>
    </table>

* **Host APIs supported**

    - `N/A`

* **Used by**

    - `N/A`


* **Platforms supported**

    <table>
    <tr>
        <td>JVM</td>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="innative"></a>[inNative](https://github.com/innative-sdk/innative) <sup>[top⇈](#contents)</sup>
> An AOT (ahead-of-time) compiler for WebAssembly that creates C compatible binaries, either as sandboxed plugins you can dynamically load, or as stand-alone executables that interface directly with the operating system.

* **Languages written in**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>AOT</td>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    <table>
    <tr>
        <td>Threads</td>
        <td>Multiple Result and Block Parameters</td>
        <td>Name Section</td>
        <td>Bulk Memory Operations</td>
        <td>Sign Extension Instructions</td>
        <td>Non-trapping Conversion Instructions</td>
    </tr>
    </table>

* **Host APIs supported**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="life"></a>[Life](https://github.com/perlin-network/life) <sup>[top⇈](#contents)</sup>
> Life is a secure & fast WebAssembly VM built for decentralized applications, written in Go by Perlin Network.

* **Languages written in**

    <table>
    <tr>
        <td>Go</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="lucet"></a>[Lucet](https://github.com/fastly/lucet) <sup>[top⇈](#contents)</sup>
> Lucet is a native WebAssembly compiler and runtime. It is designed to safely execute untrusted WebAssembly programs inside your application.

> NOTE: Lucet is now in maintenance mode. Work has been moved to [wasmtime](https://github.com/bytecodealliance/wasmtime/).

* **Languages written in**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Cranelift</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>AOT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **Non-web standards**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
    </tr>
    </table>


## <a name="wasm3"></a>[Wasm3](https://github.com/wasm3/wasm3) <sup>[top⇈](#contents)</sup>
> 🚀 A high performance WebAssembly interpreter

* **Languages written in**

    <table>
    <tr>
        <td>C</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    <table>
    <tr>
        <td>Python</td>
        <td>C/C++</td>
        <td>Rust</td>
        <td>Go</td>
        <td>Zig</td>
        <td>Swift</td>
        <td>C#/.Net</td>
    </tr>
    </table>

* **Non-MVP features supported**

    <table>
    <tr>
        <td>Multi-Value</td>
        <td>Bulk Memory Operations</td>
        <td>Sign-extension operators</td>
        <td>Non-trapping conversions</td>
        <td>Name Section</td>
    </tr>
    </table>

* **Host APIs supported**

    <table>
    <tr>
        <td>WASI</td>
        <td>Custom</td>
    </tr>
    </table>

* **Non-web standards**

    <table>
    <tr>
        <td>WASI</td>
        <td>Gas Metering</td>
    </tr>
    </table>

* **Used by**

    - [wasmcloud](https://wasmcloud.dev/) - A platform for writing portable business logic
    - [Shareup](https://shareup.app/) - Fast, private sharing for everyone
    - [WowCube](https://wowcube.com/) - An nnovative console and the gaming platform
    - [txiki.js](https://github.com/saghul/txiki.js) -A small and powerful JavaScript runtime

* **Platforms supported**

    <table>
    <tr>
        <td>Windows</td>
        <td>Linux<br/>(any arch)</td>
        <td>macOS<br/>(any arch)</td>
        <td>FreeBSD<br/>(any arch)</td>
        <td>Android</td>
        <td>OpenWRT</td>
        <td>SBC/MCU</td>
        <td>Arduino</td>
    </tr>
    </table>



## <a name="motor"></a>[Motor](https://github.com/penberg/motor) <sup>[top⇈](#contents)</sup>
> Motor is a WebAssembly runtime, which aims for secure and efficient execution of WebAssembly programs

* **Languages written in**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Dynasm</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
    </tr>
    </table>


## <a name="py-wasm"></a>[py-wasm](https://github.com/ethereum/py-wasm) <sup>[top⇈](#contents)</sup>
> A python implementation of the WebAssembly interpreter

* **Languages written in**

    <table>
    <tr>
        <td>Python</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="serverless-wasm"></a>[Serverless wasm](https://github.com/Geal/serverless-wasm) <sup>[top⇈](#contents)</sup>
> A small demo of Web Assembly's potential outside of browsers

* **Languages written in**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Wasmi</td>
        <td>Cranelift</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="swam"></a>[Swam](https://github.com/satabin/swam) <sup>[top⇈](#contents)</sup>
> WebAssembly engine in Scala

* **Languages written in**

    <table>
    <tr>
        <td>Scala</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="vmir"></a>[VMIR](https://github.com/andoma/vmir) <sup>[top⇈](#contents)</sup>
> VMIR is a standalone library written in C that can parse and execute WebAssembly and LLVM Bitcode files

* **Languages written in**

    <table>
    <tr>
        <td>C</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`
    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="wac"></a>[wac](https://github.com/kanaka/wac) <sup>[top⇈](#contents)</sup>
> A Minimal WebAssembly interpreter written in C.

* **Languages written in**

    <table>
    <tr>
        <td>C</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="wagon"></a>[wagon](https://github.com/go-interpreter/wagon) <sup>[top⇈](#contents)</sup>
> Wagon is a WebAssembly-based interpreter in Go, for Go.

* **Languages written in**

    <table>
    <tr>
        <td>Go</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="wakit"></a>[WAKit](https://github.com/akkyie/WAKit) <sup>[top⇈](#contents)</sup>
> A WebAssembly runtime written in Swift.

* **Languages written in**

    <table>
    <tr>
        <td>Swift</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
    </tr>
    </table>

## <a name="warpy"></a>[Warpy](https://github.com/kanaka/warpy) <sup>[top⇈](#contents)</sup>
> WebAssembly interpreter in RPython.

* **Languages written in**

    <table>
    <tr>
        <td>RPython</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>RPython</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="wasmedge"></a>[WasmEdge](https://github.com/WasmEdge/WasmEdge) <sup>[top⇈](#contents)</sup>
> A lightweight, high-performance, and extensible WebAssembly runtime for cloud native, edge, and decentralized applications. Project under CNCF.

* **Languages written in**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreter</td>
        <td>AOT</td>
    </tr>
    </table>

* **Interoperability with other languages**

   <table>
    <tr>
        <td>Solidity</td>
        <td>Rust</td>
        <td>C/C++</td>
        <td>Go/TinyGo</td>
        <td>JavaScript</td>
        <td>Python</td>
        <td>Grain</td>
        <td>Swift</td>
        <td>Zig</td>
        <td>Ruby</td>
    </tr>
    </table>

* **Non-MVP features supported**

    <table>
    <tr>
        <td>Bulk Memory Operations</td>
        <td>SIMD</td>
        <td>Multi-Memory</td>
        <td>Multi-Value</td>
        <td>Reference Types</td>
        <td>Sign Extension Instructions</td>
        <td>Non-Trapping Float-to-Int Conversions</td>
        <td>Mutable Global</td>
    </tr>
    </table>

* **Host APIs supported**

    <table>
    <tr>
        <td>WASI</td>
        <td>Networking Socket</td>
        <td>TensorFlow</td>
        <td>Command Interface</td>
        <td>Image Processing</td>
    </tr>
    </table>

* **Non-web standards**

   <table>
    <tr>
        <td>WASI</td>
        <td>Gas Metering</td>
        <td>Ethereum Environment Interface</td>
        <td>Oasis</td>
        <td>Substrate</td>
    </tr>
    </table>

* **Used by**

    - [Suborbital](https://blog.suborbital.dev/suborbital-wasmedge)
    - [crun](https://github.com/containers/crun/pull/774)
    - [SuperEdge](https://github.com/superedge/superedge/pull/335)
    - [OpenYurt](https://github.com/openyurtio/openyurt.io/pull/85)
    - [Dapr](https://www.infoq.com/articles/webassembly-dapr-wasmedge/)
    - [Yomo](https://github.com/yomorun/yomo-wasmedge-tensorflow)
    - [Oasis ETH ParaTime](https://medium.com/oasis-protocol-project/the-oasis-eth-paratime-is-live-on-mainnet-33d8713ec870)

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
        <td>Android</td>
        <td>OpenHarmony</td>
        <td>seL4 RTOS</td>
    </tr>
    </table>

## <a name="wasmer"></a>[Wasmer](https://github.com/wasmerio/wasmer) <sup>[top⇈](#contents)</sup>
> Wasmer is a standalone WebAssembly runtime for running WebAssembly outside of the browser, supporting WASI and Emscripten.

* **Languages written in**

    <table>
    <tr>
        <td>Rust</td>
        <td>C++</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Singlepass</td>
        <td>Cranelift (Default)</td>
        <td>LLVM</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>JIT</td>
        <td>AOT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    <table>
    <tr>
        <td>Rust</td>
        <td>PHP</td>
        <td>C</td>
        <td>C++</td>
        <td>Python</td>
        <td>Go</td>
        <td>PHP</td>
        <td>Java</td>
        <td>Ruby</td>
        <td>Postgres</td>
        <td>C#/.Net</td>
        <td>Elixir</td>
        <td>R</td>
        <td>D</td>
        <td>Swift</td>
    </tr>
    </table>

* **Non-MVP features supported**

    <table>
    <tr>
        <td>Threads</td>
        <td>SIMD</td>
        <td>Multi Value returns</td>
        <td>Name Section</td>
        <td>Bulk Memory Operations</td>
        <td>Sign Extension Instructions</td>
    </tr>
    </table>

* **Host APIs supported**

    <table>
    <tr>
        <td>Emscripten</td>
        <td>WASI</td>
    </tr>
    </table>

* **Non-web standards**

    <table>
    <tr>
        <td>WASI</td>
        <td>wasm-c-api</td>
    </tr>
    </table>

* **Used by**

    - [Spacemesh Virtual Machine](https://github.com/spacemeshos/svm) - A Spacemesh smart contracts vm
    - [CosmWasm](https://github.com/CosmWasm/cosmwasm) - A Cosmos-compatible library for running wasm smart contracts
    - [NEAR Protocol](https://github.com/near/nearcore) - The reference client for NEAR protocol
    - [Dprint](https://github.com/dprint/dprint) - Pluggable and configurable code formatting platform

* **Platforms supported**

    <table>
    <tr>
        <td>Linux (x64, aarch64, x86)</td>
        <td>macOS (x64, arm64)</td>
        <td>Windows (x64, x86)</td>
        <td>FreeBSD (x64)</td>
        <td>Android</td>
    </tr>
    </table>

## <a name="wasmi"></a>[Wasmi](https://github.com/paritytech/wasmi) <sup>[top⇈](#contents)</sup>
> A Wasm interpreter.

* **Languages written in**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    <table>
    <tr>
        <td>Mutable Globals</td>
        <td>Sign-extension operators</td>
        <td>Non-trapping conversions</td>
        <td>Multi-Value</td>
        <td>Bulk Memory Operations</td>
        <td>Reference Types</td>
        <td>Tail Calls</td>
        <td>Extended Const</td>
    </tr>
    </table>

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **Used by**

    <table>
    <tr>
        <td>Substrate</td>
        <td>smoldot</td>
        <td>Ayaka Game Engine</td>
    </tr>
    </table>

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
        <td>WebAssembly</td>
    </tr>
    </table>

## <a name="wasmo"></a>[Wasmo](https://github.com/appcypher/wasmo) <sup>[top⇈](#contents)</sup>
> A WebAssembly Runtime and Compiler based on LLVM.

* **Languages written in**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>macOS</td>
    </tr>
    </table>

## <a name="wasmrt"></a>[wasmrt](https://github.com/rhitchcock/wasmrt) <sup>[top⇈](#contents)</sup>
> wasmrt is a runtime built for native execution of WebAssembly modules (virtualized at first, eventually JIT).

* **Languages written in**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wasmtime"></a>[Wasmtime](https://github.com/CraneStation/wasmtime) <sup>[top⇈](#contents)</sup>
> Wasmtime is a standalone wasm-only runtime for WebAssembly, using the Cranelift JIT

* **Languages written in**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Cranelift</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    <table>
    <tr>
        <td>Python</td>
    </tr>
    </table>

* **Non-MVP features supported**

    <table>
    <tr>
        <td>Interface types</td>
    </tr>
    </table>

* **Host APIs supported**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **Non-web standards**

    <table>
    <tr>
        <td>WASI</td>
        <td>wasm-c-api</td>
    </tr>
    </table>

* **Used by**

    - [Wasmi](https://github.com/paritytech/wasmi): an efficient WebAssembly interpreter that is used by [Substrate](https://github.com/paritytech/substrate), a next-generation framework for blockchain innovation.

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wasmvm1"></a>[WasmVM](https://github.com/WasmVM/WasmVM) <sup>[top⇈](#contents)</sup>
> An unofficial standalone WebAssembly process virtual machine

* **Languages written in**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wasmvm2"></a>[wasmvm](https://github.com/kogai/wasvm) <sup>[top⇈](#contents)</sup>
> WebAssembly Virtual Machine, which aim to fit embedded systems.

* **Languages written in**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Life</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wavm"></a>[WAVM](https://github.com/WAVM/WAVM) <sup>[top⇈](#contents)</sup>
> WebAssembly Virtual Machine, which aim to fit embedded systems.

* **Languages written in**

    <table>
    <tr>
        <td>C++</td>
        <td>Python</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    <table>
    <tr>
        <td>Threads</td>
        <td>SIMD</td>
        <td>Multiple Result and Block Parameters</td>
        <td>Exception Handling</td>
        <td>Name Section</td>
        <td>Reference Types</td>
        <td>Bulk Memory Operations</td>
        <td>Sign Extension Instructions</td>
    </tr>
    </table>

* **Host APIs supported**

    <table>
    <tr>
        <td>WASI</td>
        <td>Emscripten</td>
        <td>WAVIX</td>
    </tr>
    </table>

* **Non-web standards**

    - [x] WASI

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="webassembly"></a>[webassembly](https://github.com/dcodeIO/webassembly) <sup>[top⇈](#contents)</sup>
> An experimental, minimal toolkit and runtime on top of node to produce and run WebAssembly modules

* **Languages written in**

    <table>
    <tr>
        <td>JavaScript</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>NodeJS(V8)</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="wamr"></a>[WAMR](https://github.com/bytecodealliance/wasm-micro-runtime) <sup>[top⇈](#contents)</sup>
> WebAssembly Micro Runtime (WAMR) is a standalone WebAssembly (WASM) runtime with small footprint

* **Languages written in**

    <table>
    <tr>
        <td>C</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
        <td>AOT-Modules</td>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - [Non-trapping float-to-int conversions](https://github.com/WebAssembly/nontrapping-float-to-int-conversions)
    - [Sign-extension operators](https://github.com/WebAssembly/sign-extension-ops)
    - [Bulk memory operations](https://github.com/WebAssembly/bulk-memory-operations)
    - [Shared memory](https://github.com/WebAssembly/threads/blob/main/proposals/threads/Overview.md#shared-linear-memory)
    - [Multi-value](https://github.com/WebAssembly/multi-value)
    - [Tail-call](https://github.com/WebAssembly/tail-call)


* **Host APIs supported**

    - [wasm-c-api](https://github.com/WebAssembly/wasm-c-api)

* **Non-web standards**

    - [x] WASI

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
        <td>AliOS-Things</td>
        <td>Android</td>
        <td>Linux-SGX</td>
        <td>Nuttx</td>
        <td>VxWorks</td>
        <td>Zephyr</td>
    </tr>
    </table>



## <a name="twvm"></a>[TWVM](https://github.com/Becavalier/TWVM) <sup>[top⇈](#contents)</sup>
>A tiny and efficient WebAssembly virtual machine.

* **Languages written in**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    - `N/A`

* **Host APIs supported**

    - `N/A`

* **Non-web standards**

    - `N/A`

* **Used by**

    - `N/A`

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>



## <a name="wazero"></a>[wazero](https://wazero.io) <sup>[top⇈](#contents)</sup>
> wazero is a WebAssembly 1.0 and 2.0 spec compliant runtime written in Go, with zero platform dependencies.

* **Languages written in**

    <table>
    <tr>
        <td>Go</td>
    </tr>
    </table>

* **Compiler framework**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **Compilation / Execution modes**

    <table>
    <tr>
        <td>Interpreted</td>
        <td>JIT</td>
    </tr>
    </table>

* **Interoperability with other languages**

    - `N/A`

* **Non-MVP features supported**

    <table>
    <tr>
        <td>Bulk Memory Operations</td>
        <td>Import/Export of Mutable Globals</td>
        <td>Sign-extension operators</td>
        <td>Multi-Value Returns</td>
        <td>Name Section</td>
        <td>Non-trapping float-to-int conversions</td>
        <td>Reference Types</td>
        <td>SIMD</td>
    </tr>
    </table>

* **Host APIs supported**

    <table>
    <tr>
        <td>AssemblyScript</td>
        <td>WASI</td>
    </tr>
    </table>

* **Non-web standards**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **Used by**

    - [dapr](https://github.com/dapr/dapr) - APIs that simplify microservice connectivity
    - [trivy](https://github.com/aquasecurity/trivy) - vulnerability/misconfiguration/secret scanner for containers and other artifacts
    - [wapc-go](https://github.com/wapc/wapc-go) - WebAssembly Host Runtime for waPC-compliant modules

* **Platforms supported**

    <table>
    <tr>
        <td>FreeBSD (amd64)</td>
        <td>Linux (amd64, arm64, riscv64)</td>
        <td>macOs (amd64)</td>
        <td>Windows (amd64)</td>
    </tr>
    </table>
-------------------

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Steve Akinyemi](https://github.com/appcypher) has waived all copyright and related or neighboring rights to this work.
