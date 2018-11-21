## Building

    $ nix-build

## Running

    [hydra@hydra:~/nixos-channel-scripts]$ ./result/bin/mirror-nixos-branch --releaseUrl https://hydra.aira.life/job/aira/core/tested/latest-finished

updates aira-unstable channel (https://hydra.aira.life/channels/aira-unstable/)

## Running
    [hydra@hydra:~/nixos-channel-scripts]$ ./result/bin/mirror-nixos-branch --release
    
updates aira-release channel (https://hydra.aira.life/channels/aira-release/) with hydra evaluation result for airapkgs revision from (https://github.com/airalab/aira/)
