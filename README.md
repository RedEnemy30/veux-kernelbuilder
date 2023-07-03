# veux-kernelbuilder

## Build using Actions
1. Fork this repo
2. Settings tab > Actions > General > Allow all actions and reusable workflows > Save
3. Run workflow
- If you want to integrate KernelSU to the build, uncomment `KSU=1` in `build.sh`
  
## Build on local host
`git clone https://github.com/cachiusa/veux-kernelbuilder`
`./build.sh`
### Usage for `build.sh`:
- (leave empty)  => run everything from start to end
- `-ksu` => same, but integrates KernelSU
- `getsource`/`gettools`/`startbuild`/`finalize` => run a specific section of build process

