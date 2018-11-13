# Ansible CheatSheet Update Ideas

### Ansible Vault
Create a new encrypted file	
> \# ansible-vault create filename

Edit an existing encrypted file
> \# ansible-vault edit filename

Change vault password		
> \# ansible-vault rekey filename

Encrypt existing file		
> \# ansible-vault encrypt filename --output=OUTPUT_FILE (optional)

View encrypted file		
> \# ansible-vault view filename

Decrypt file permanently		
> \# ansible-vault decrypt filename --output=OUTPUT_FILE (optional)

Reference secret.yml in playbook
```
  vars_files: 
    - secret.yml
```

Run playbook with vault password prompt
> \# ansible-playbook  --ask-vault-pass myplaybook.yml

### Tags

### Blocks

### Ignore_Errors

### Failed_When

### Changed_When
