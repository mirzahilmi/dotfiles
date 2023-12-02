#### Export public & private GPG keys
```
gpg --output public.pgp --armor --export <email>
gpg --output private.pgp --armor --export-secret-keys <email>
```