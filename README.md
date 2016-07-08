# Paint Tool SAI Decrypter

A proof-of-concept program for decrypting Paint Tool SAI files.

The program was re-created in C for ease of implementation and for speed. The Python script took about 45.7 seconds to run on larger (~32 MB) files; it now processes those same files in under 1 second.

The code currently only decrypts .SAI file data and saves it to a .PTSD file without converting it to another format, such as a PSD or CLIP file. I may add a PoC converter at some point, but this is what I've got so far.
### Usage
```
ptsd.exe [filename].sai
```
