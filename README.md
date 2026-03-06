Just want everything? 
```
gh repo list stoicstudio  --json sshUrl | convertfrom-json | Select-Object -ExpandProperty sshUrl | % { git clone $_ }
```
