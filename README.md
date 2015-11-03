# HPE OneView golang bindings

HPE OneView allows you to treat your physical infrastructure as code, and now
you can integrate your favorite tools based in golang with HPE OneView.

## Testing your changes

### From a container
```
USE_CONTAINER=1 make test
```

### From your local system
* Install golang 1.5 or better
* Install go pakcages listed in .travis.yml
```
make test
```

## Contributing

Want to hack on oneview-golang? Please start with the [Contributing Guide](https://github.com/HewlettPackard/docker-machine-oneview/blob/master/CONTRIBUTING.md).

This code base is primarily consumed and used by the docker-machine-oneview project.  We will follow contribution standards set by this project.

## License
This project is licensed under the Apache License, Version 2.0.  See LICENSE for full license text.
