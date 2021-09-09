## README 

A Nix flake for building Clarinet v15.04 from the provided release [zip](https://github.com/hirosystems/clarinet/releases/tag/v0.15.4). 

Have Nix installed with flakes enabled.  
Copy the zip to your local directory.  
Run `nix build`. The first time, this will take a while as it indexes nixpkgs and downloads the required packages.  
Clarinet will be available under `result/bin/clarinet`. 

See the Nix flake [reference](https://nixos.org/manual/nix/unstable/command-ref/new-cli/nix3-flake.html) for commands and advanced usage.
