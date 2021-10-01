# docker.fish
🐟 Fish completions for Docker for nix home-manager config
```nix
programs = {
    fish = {
      plugins = [
    {
      name = "docker.fish";
      src = pkgs.fetchgit {
        url = "https://github.com/Cyunrei/docker.fish";
        rev = "7dce1b32973833ffa7024b740869e826357b3082";
        sha256 = "090cb77kwxw867rrp6f3rh623vflh22l24r83dgxav55kakncz90";
      };
    }
  ];
 }
};
```
