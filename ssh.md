# windows upload public key (Use Powershell)
`Get-Content $env:USERPROFILE\.ssh\id_rsa.pub | ssh user@host "cat >> .ssh/authorized_keys"`  
`Get-Content $env:USERPROFILE\.ssh\id_rsa.pub | ssh @ "cat >> .ssh/authorized_keys"`

# upload public key
`ssh-copy-id -i ~/.ssh/id_rsa.pub user@host`
