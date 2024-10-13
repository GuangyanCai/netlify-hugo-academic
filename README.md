# Guide

## Dependencies

Install scoop:
```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
iwr -useb get.scoop.sh | iex
```
Install dependencies:
```bash
scoop install git go nodejs pipx
scoop install hugo-extended@0.119.0
```

For importing publications:
```bash
pip install academic==0.8.1
```

## View
```bash
hugo server -D
```

## Import publications
```bash
academic import --bibtex publications.bib
``` 
