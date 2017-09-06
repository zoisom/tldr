# zipcloak

> The encrypts files in an existing zip archive.

- Encrypts the contents so that only root users can extract the contents:

`zipcloak {{archive.zip}}`

- Remove encrypts form archive:

`zipcloak -d {{archive.zip}}`

- Eject encrypts archive into new file:

`zipcloak {{archive.zip}} -o {{archive_new.zip}}`
