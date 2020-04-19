# Pdf to text
## Usage
Convert input.pdf to output.txt. Note the `-i` to attach stdin and stdout.
```
docker run --rm -i arjobsen/pdftotext < input.pdf > output.txt
```

Convert input.pdf and print to stdout.
```
docker run --rm -i arjobsen/pdftotext < input.pdf
```

Execute with options. E.g. convert only the first page.
```
docker run --rm -i arjobsen/pdftotext -l 1 < input.pdf
```

See command help and version
```
docker run --rm  arjobsen/pdftotext -h
```

## Links
https://www.mankier.com/1/pdftotext

https://hub.docker.com/_/alpine
