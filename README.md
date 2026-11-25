# perl-tool-template
#Build the tool into a docker and run from there
```
$ docker build -t tool:0.1 .
```
## then
```
perl-tool-template $ docker run tool:0.1 tool
ERR: Must specify action(-a)
Actions: SomeFunction 
````

## License

This project is released into the public domain under the [Unlicense](https://unlicense.org). See [LICENSE](LICENSE) for details.
