# nixos-config

## How to use

Install home-manager as standalone program

```nix
...
  environment.systemPackages = with pkgs; [
...
    home-manager
    # editors
...
  ];
...
```

Clone the repo and go inside the root dir

```sh
git@github.com:aryuuu/nixos-config.git && cd nixos-config
```

Run home-manager

```sh
home-manager switch --flake .#fatt
```
