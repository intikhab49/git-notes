# Line endings on mixed platforms

Set `core.autocrlf=input` on Unix and `true` on Windows, or better, commit a .gitattributes with `* text=auto`. The attributes file is authoritative and travels with the repo, unlike per-machine config.
