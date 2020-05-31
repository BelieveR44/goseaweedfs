# goseaweedfs

本地fork到这里 以便兼容老的weedfs

## Installation
```
go get -u github.com/linxGnu/goseaweedfs
```

## Usage
Please refer to [Test Cases](https://github.com/linxGnu/goseaweedfs/blob/master/seaweed_test.go) for sample code.

## Supported

- [x] Grow
- [x] Status
- [x] Cluster Status
- [x] Filer
- [x] Upload
- [x] Submit
- [x] Delete
- [x] Replace
- [x] Upload large file with builtin manifest handler, auto file split and chunking
- [ ] Admin Operations (mount, unmount, delete volumn, etc)

## Contributing
Please issue me for things gone wrong or:

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
