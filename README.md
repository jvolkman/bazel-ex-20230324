```
bazel run //:test
```

`test` uses `value_retriever` which gets data from a pre-built, shared lib `libvalsrc.so`

The included `libvalsrc.so` was built on a modern x86_64 ubuntu machine, so it may or may not work for you.
