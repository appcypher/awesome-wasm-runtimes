# Awesome WebAssembly Runtimes ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

This repo contains a list of virtual machines and tools that execute the WebAssembly(wasm) format and/or compile it to executable machine code :octocat:

#### Legend
:rocket: - Active development</br>
:sleeping: - Unmaintained (been more than a year since last commit)</br>

## CONTENTS

- [CMM of Wasm](#cmm) <sup><sup>:sleeping:</sup></sup></br>
- [EOSVM](#eosvm) <sup><sup>:rocket:</sup></sup></br>
- [FDVM](#fdvm) <sup><sup>:sleeping:</sup></sup></br>
- [GraalWASM](#graalwasm) <sup><sup>:rocket:</sup></sup></br>
- [Happy New Moon With Report](#happy-new-moon-with-report) <sup><sup>:rocket:</sup></sup></br>
- [inNative](#innative) <sup><sup>:rocket:</sup></sup></br>
- [Life](#life) <sup><sup>:rocket:</sup></sup></br>
- [Lucet](#lucet) <sup><sup>:rocket:</sup></sup></br>
- [wasm3](#wasm3) <sup><sup>:rocket:</sup></sup></br>
- [Motor](#motor) <sup><sup>:sleeping:</sup></sup></br>
- [py-wasm](#py-wasm) <sup><sup>:rocket:</sup></sup></br>
- [Serverless Wasm](#serverless-wasm) <sup><sup>:sleeping:</sup></sup></br>
- [Swam](#swam) <sup><sup>:rocket:</sup></sup></br>
- [VMIR](#vmir) <sup><sup>:sleeping:</sup></sup></br>
- [wac](#wac) <sup><sup>:rocket:</sup></sup></br>
- [Wagon](#wagon) <sup><sup>:rocket:</sup></sup></br>
- [WAKit](#wakit) <sup><sup>:rocket:</sup></sup></br>
- [Warpy](#warpy) <sup><sup>:rocket:</sup></sup></br>
- [Wasmer](#wasmer) <sup><sup>:rocket:</sup></sup></br>
- [Wasmo](#wasmo) <sup><sup>:rocket:</sup></sup></br>
- [WasmRT](#wasmrt) <sup><sup>:sleeping:</sup></sup></br>
- [Wasmtime](#wasmtime) <sup><sup>:rocket:</sup></sup></br>
- [WasmVM](#wasmvm1) <sup><sup>:rocket:</sup></sup></br>
- [WasmVM](#wasmvm2) <sup><sup>:rocket:</sup></sup></br>
- [WAVM](#wavm) <sup><sup>:rocket:</sup></sup></br>
- [WebAssembly](#webassembly) <sup><sup>:sleeping:</sup></sup></br>
- [WebAssembly Micro Runtime](#webassembly-micro-runtime-top) <sup><sup>:rocket:</sup></sup></br>
- [TWVM](#twvm) <sup><sup>:rocket:</sup></sup></br>
- [SSVM](#SSVM) <sup><sup>:rocket:</sup></sup></br>

----------------

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


## <a name="wasm3"></a>[wasm3/wasm3](https://github.com/wasm3/wasm3) <sup>[top⇈](#contents)</sup>
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
        <td>Windows</td>
        <td>Android</td>
        <td>OpenWRT</td>
        <td>SBC/MCU</td>
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
        <td>Cranelift (Primary)</td>
        <td>Dynasm.rs</td>
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

    <table>
    <tr>
        <td>PHP</td>
        <td>C</td>
        <td>C++</td>
        <td>Python</td>
        <td>Go</td>
        <td>PHP</td>
        <td>Ruby</td>
        <td>Postgres</td>
        <td>C#/.Net</td>
        <td>R</td>
        <td>Swift</td>
    </tr>
    </table>

* **Non-MVP features supported**

    <table>
    <tr>
        <td>SIMD</td>
        <td>Threads</td>
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

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
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

## <a name="wasmo"></a>[Wasmo](https://github.com/appcypher/wasmo) <sup>[top⇈](#contents)</sup>
> An Embeddable WebAssembly VM

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
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
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
        <td>C++</td>
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

    - `N/A`

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


## <a name="#wamr"></a>[WebAssembly Micro Runtime](https://github.com/intel/wasm-micro-runtime) <sup>[top⇈](#contents)</sup>
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



## <a name="TWVM"></a>[TWVM](https://github.com/Becavalier/TWVM) <sup>[top⇈](#contents)</sup>
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

## <a name="SSVM"></a>[SSVM](https://github.com/second-state/ssvm) <sup>[top⇈](#contents)</sup>
> A WebAssembly runtime optimized for server-side applications.

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
    </tr>
    </table>

* **Interoperability with other languages**

   <table>
    <tr>
        <td>Solidity</td>
        <td>Rust</td>
        <td>C++</td>
    </tr>
    </table> 

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
        <td>Ethereum Environment Interface</td>
    </tr>
    </table> 

* **Used by**

    <table>
    <tr>
        <td>Devchain</td>
    </tr>
    </table> 

* **Platforms supported**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>
-------------------

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Steve Akinyemi](https://github.com/appcypher) has waived all copyright and related or neighboring rights to this work.
