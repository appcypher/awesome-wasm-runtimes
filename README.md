# Awesome WebAssembly Runtimes ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

This repo contains a list of virtual machines and tools that execute the WebAssembly(wasm) format and/or compile it to executable machine code :octocat:

#### Legend
:rocket: - Active development</br>
:sleeping: - Unmaintained (been more than a year since last commit)</br>

## CONTENTS
:sleeping: [CMM of Wasm](#cmm)</br>
:rocket: [EOSVM](#eosvm)</br>
:sleeping: [FDVM](#fdvm)</br>
:rocket: [inNative](#innative)</br>
:sleeping: [Life](#life)</br>
:rocket: [Lucet](#lucet)</br>
:rocket: [M3](#m3)</br>
:sleeping: [Motor](#motor)</br>
:rocket: [py-wasm](#py-wasm)</br>
:sleeping: [Serverless Wasm](#serverless-wasm)</br>
:rocket: [Swam](#swam)</br>
:sleeping: [VMIR](#vmir)</br>
:rocket: [wac](#wac)</br>
:sleeping: [Wagon](#wagon)</br>
:rocket: [WAKit](#wakit)</br>
:rocket: [WAMR](#wasm-micro-runtime)</br>
:rocket: [Warpy](#warpy)</br>
:rocket: [Wasmer](#wasmer)</br>
:rocket: [Wasmo](#wasmo)</br>
:sleeping: [WasmRT](#wasmrt)</br>
:rocket: [Wasmtime](#wasmtime)</br>
:sleeping: [WasmVM](#wasmvm1)</br>
:rocket: [WasmVM](#wasmvm2)</br>
:rocket: [WAVM](#wavm)</br>
:sleeping: [WebAssembly](#webassembly)</br>

----------------

## <a name="cmm"></a>[CMM of Wasm](https://github.com/SimonJF/cmm_of_wasm) <sup>[top⇈](#contents)</sup>
> A compiler from WebAssembly to native code, via the OCaml backend.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>OCaml</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>OCaml Compiler</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>AOT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
    </tr>
    </table>

## <a name="eosvm"></a>[EOSVM](https://github.com/EOSIO/eos-vm) <sup>[top⇈](#contents)</sup>
> EOS VM is designed from the ground up for the high demands of blockchain applications which require far more from a WebAssembly engine than those designed for web browsers or standards development.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="fdvm"></a>[FDVM](https://github.com/funcdef/fdvm) <sup>[top⇈](#contents)</sup>
> WASM runtime to develop server-side WebAssembly applications.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>JavaScript</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>NodeJS(V8)</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>



## <a name="innative"></a>[inNative](https://github.com/innative-sdk/innative) <sup>[top⇈](#contents)</sup>
> An AOT (ahead-of-time) compiler for WebAssembly that creates C compatible binaries, either as sandboxed plugins you can dynamically load, or as stand-alone executables that interface directly with the operating system.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>AOT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="life"></a>[Life](https://github.com/perlin-network/life) <sup>[top⇈](#contents)</sup>
> Life is a secure & fast WebAssembly VM built for decentralized applications, written in Go by Perlin Network.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Go</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="lucet"></a>[Lucet](https://github.com/fastly/lucet) <sup>[top⇈](#contents)</sup>
> Lucet is a native WebAssembly compiler and runtime. It is designed to safely execute untrusted WebAssembly programs inside your application.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Cranelift</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>AOT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **NON-WEB STANDARDS**

    - [x] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
    </tr>
    </table>


## <a name="m3"></a>[M3/Wasm](https://github.com/soundandform/m3) <sup>[top⇈](#contents)</sup>
> WebAssembly interpreter written in C using a novel, high performance interpreter topology.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>



## <a name="motor"></a>[Motor](https://github.com/penberg/motor) <sup>[top⇈](#contents)</sup>
> Motor is a WebAssembly runtime, which aims for secure and efficient execution of WebAssembly programs

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Dynasm</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
    </tr>
    </table>


## <a name="py-wasm"></a>[py-wasm](https://github.com/ethereum/py-wasm) <sup>[top⇈](#contents)</sup>
> A python implementation of the WebAssembly interpreter

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Python</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="serverless-wasm"></a>[py-wasm](https://github.com/Geal/serverless-wasm) <sup>[top⇈](#contents)</sup>
> A small demo of Web Assembly's potential outside of browsers

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Wasmi</td>
        <td>Cranelift</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="swam"></a>[Swam](https://github.com/satabin/swam) <sup>[top⇈](#contents)</sup>
> WebAssembly engine in Scala

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Scala</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="vmir"></a>[VMIR](https://github.com/andoma/vmir) <sup>[top⇈](#contents)</sup>
> VMIR is a standalone library written in C that can parse and execute WebAssembly and LLVM Bitcode files

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`
    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="wac"></a>[wac](https://github.com/kanaka/wac) <sup>[top⇈](#contents)</sup>
> A Minimal WebAssembly interpreter written in C.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="wagon"></a>[wagon](https://github.com/go-interpreter/wagon) <sup>[top⇈](#contents)</sup>
> Wagon is a WebAssembly-based interpreter in Go, for Go.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Go</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="wakit"></a>[WAKit](https://github.com/akkyie/WAKit) <sup>[top⇈](#contents)</sup>
> A WebAssembly runtime written in Swift.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Swift</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
    </tr>
    </table>

## <a name="wamr"></a>[WebAssembly Micro Runtime](https://github.com/intel/wasm-micro-runtime) <sup>[top⇈](#contents)</sup>
> WebAssembly Micro Runtime (WAMR) is a standalone WebAssembly (WASM) runtime with small footprint

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="warpy"></a>[Warpy](https://github.com/kanaka/warpy) <sup>[top⇈](#contents)</sup>
> WebAssembly Micro Runtime (WAMR) is a standalone WebAssembly (WASM) runtime with small footprint

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>RPython</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>RPython</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>


## <a name="wasmer"></a>[Wasmer](https://github.com/wasmerio/wasmer) <sup>[top⇈](#contents)</sup>
> Wasmer is a standalone WebAssembly runtime for running WebAssembly outside of the browser, supporting WASI and Emscripten.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Rust</td>
        <td>C++</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Cranelift (Primary)</td>
        <td>Dynasm.rs</td>
        <td>LLVM</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

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

* **NON-MVP FEATURES SUPPORTED**

    <table>
    <tr>
        <td>SIMD</td>
    </tr>
    </table>

* **HOST INTERFACES SUPPORTED**

    <table>
    <tr>
        <td>Emscripten</td>
        <td>WASI</td>
    </tr>
    </table>

* **NON-WEB STANDARDS**

    - [x] WASI
    - [x] wasm-c-api

* **USED BY**

    - [Spacemesh Virtual Machine](https://github.com/spacemeshos/svm) - A Spacemesh smart contracts vm

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wasmo"></a>[Wasmo](https://github.com/appcypher/wasmo) <sup>[top⇈](#contents)</sup>
> An Embeddable WebAssembly VM

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wasmrt"></a>[wasmrt](https://github.com/rhitchcock/wasmrt) <sup>[top⇈](#contents)</sup>
> wasmrt is a runtime built for native execution of WebAssembly modules (virtualized at first, eventually JIT).

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wasmtime"></a>[Wasmtime](https://github.com/CraneStation/wasmtime) <sup>[top⇈](#contents)</sup>
> Wasmtime is a standalone wasm-only runtime for WebAssembly, using the Cranelift JIT

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Cranelift</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    <table>
    <tr>
        <td>Python</td>
    </tr>
    </table>

* **NON-MVP FEATURES SUPPORTED**

    <table>
    <tr>
        <td>Interface types</td>
    </tr>
    </table>

* **HOST INTERFACES SUPPORTED**

    <table>
    <tr>
        <td>WASI</td>
    </tr>
    </table>

* **NON-WEB STANDARDS**

    - [x] WASI
    - [x] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wasmvm1"></a>[WasmVM](https://github.com/WasmVM/WasmVM) <sup>[top⇈](#contents)</sup>
> An unofficial standalone WebAssembly process virtual machine

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C++</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Custom</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wasmvm2"></a>[wasmvm](https://github.com/kogai/wasvm) <sup>[top⇈](#contents)</sup>
> WebAssembly Virtual Machine, which aim to fit embedded systems.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>Rust</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>Life</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>Interpreted</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - [ ] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="wavm"></a>[WAVM](https://github.com/WAVM/WAVM) <sup>[top⇈](#contents)</sup>
> WebAssembly Virtual Machine, which aim to fit embedded systems.

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>C++</td>
        <td>Python</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>LLVM</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

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

* **HOST INTERFACES SUPPORTED**

    <table>
    <tr>
        <td>WASI</td>
        <td>Emscripten</td>
        <td>WAVIX</td>
    </tr>
    </table>

* **NON-WEB STANDARDS**

    - [x] WASI
    - [ ] wasm-c-api

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

    <table>
    <tr>
        <td>Linux</td>
        <td>macOS</td>
        <td>Windows</td>
    </tr>
    </table>

## <a name="webassembly"></a>[webassembly](https://github.com/dcodeIO/webassembly) <sup>[top⇈](#contents)</sup>
> An experimental, minimal toolkit and runtime on top of node to produce and run WebAssembly modules

* **LANGUAGES WRITTEN IN**

    <table>
    <tr>
        <td>JavaScript</td>
    </tr>
    </table>

* **COMPILER FRAMEWORK**

    <table>
    <tr>
        <td>NodeJS(V8)</td>
    </tr>
    </table>


* **COMPILATION / EXECUTION MODES**

    <table>
    <tr>
        <td>JIT</td>
    </tr>
    </table>

* **INTEROPERABILITY WITH OTHER LANGUAGES**

    - `N/A`

* **NON-MVP FEATURES SUPPORTED**

    - `N/A`

* **HOST INTERFACES SUPPORTED**

    - `N/A`

* **NON-WEB STANDARDS**

    - `N/A`

* **USED BY**

    - `N/A`

* **PLATFORMS SUPPORTED**

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
