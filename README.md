npmopenbsdrepackager
====================

Repackage npm packages as OpenBSD packages. Proof-of-Concept

### How does it work?

Adjust **fakedirbase** in repackager to something meaningfull on your system.
```
fakedirbase=/home/mischi/code/npm-openbsdports-repackager/fake    
```
Install dependencies.
```
pkg_add jq
```
Create a new package by calling.
```
repackager npmpkg
```
where npmpkg is a valid npm package name
