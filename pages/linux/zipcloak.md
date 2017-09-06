# zipcloak

> the encrypts files in an existing zip archive.

- encrypts the contents so that only root users can extract the contents:

`zipcloak {{archive.zip}}`

- remove encrypts form archive:

`zipcloak -d {{archive.zip}}`

- eject encrypts archive into new file:

`zipcloak {{archive.zip}} -o {{archive_new.zip}}`
