# Shared Library

## Inspect executable
```console
objdump -p main
```

### Show dynamic/undefined symbols
```console
nm -Du main
```

### Show required shared libraries
```console
ldd main
```

## References
- [Linux 編譯 shared library 的方法和注意事項](https://medium.com/fcamels-notes/linux-%E7%B7%A8%E8%AD%AF-shared-library-%E7%9A%84%E6%96%B9%E6%B3%95%E5%92%8C%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A0%85-cb35844ef331)
- [Loading Dynamic Libraries on Mac](http://clarkkromenaker.com/post/library-dynamic-loading-mac/)