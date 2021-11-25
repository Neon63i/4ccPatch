# 4cc Patching Repository

## Project Structure

- /bin/ folder contains all imported properties and edits
- /cpk/ folder contains base Konami patch & testing aesthetics cpks
- /release/ folder contains your gameplay_06 patch 

list of bins below 

## How to test patches
1. Route into your desired branch for desired release (Should be provided to you by patch maker) 
2. Take requested `.cpk` file from `/releases/` folder
3. Paste it into your `/PES21/download` folder as `4cc_06_gameplay.cpk`

## How to edit patches

1. Open GPE_REcompiler
2. Import `dt18_all.cpk` patch from `/cpk/` folder
3. Import all `.bin` files from `/bin/` folder
4. Make changes
5. ???
6. Export patch as `4cc_06_gameplay.cpk` into `/releases/` folder
7. Continue with testing steps to test

## /bin/ list

### constant_team.bin
> constant_team is present in all PES versions and therefore should be preferred as first edit option.
```
lineBreak.o - affects passing and area split into Defense - Mid - Offense 
// TODO add rest
```

## Contributing
Not to mess with master branch, always create own branch for any changes, you can do so by clicking on `master` in top left of the file list. Once your changes are considered checked and redpilled, create a pull request into master containing explanation on changed properties across all files.

## License
>He does it for free