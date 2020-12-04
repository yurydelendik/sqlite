# Build

```
mkdir bld
cd bld
../configure CC=~/bin/wasi-sdk/bin/clang CFLAGS="-D__DJGPP__ -D_WASI_EMULATED_MMAN" --host=wasm32-wasi --disable-amalgamation --disable-shared --disable-threadsafe
```

