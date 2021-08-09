# files-action

Action to upload files to azure (for internal use by Vendanor)

## Usage

```yaml
- name: Upload some file
  id: mystep
  uses: vendanor/files-action
  with:
    azureToken: ${{ secrets.AZURE_TOKEN }}
    salt: ${{ secrets.SALT }}
    input: myfile.json
    folder: 'subfolder/'
```

## Update lib

Install the dependencies, build and package it for distribution

```bash
$ npm install
$ npm run build 
$ npm run package
```
