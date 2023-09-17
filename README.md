# Home-manager

1. Instalar Nix
```
WSL:
sh <(curl -L https://nixos.org/nix/install) --no-daemon

Linux:
sh <(curl -L https://nixos.org/nix/install) --daemon
```

2. Instalar home-manager

```
nix-shell '<home-manager>' -A install
home-manager switch
```
ou
```
home-manager switch --flake .#fernando
```
