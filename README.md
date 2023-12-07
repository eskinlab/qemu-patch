# qemu-patch
This patch introduces a new monitor command, 'fizzbuzz', to the QEMU codebase.  
The 'fizzbuzz' command allows users to interact with QEMU's monitor interface during runtime.

### Run command
Run QEMU using the following command line:

```bash
./i386-softmmu/qemu-system-i386 -vnc :5 -monitor stdio
```
It will redirect the QEMU monitor to stdio.  
Type: “fizzbuzz” with a number to test :)
