# Colin's ALM Corner Service Now Azure DevOps Extensions

For more info, read the [overview](overview.md).

## Packaging

You will need to update the publisher, author and GUID for each task in this repo if you want to publish your own copy.

To package the extension, then run the following command:

```sh
yarn install
yarn run package
```

You can now upload the extension using `tfx extension publish` or via the [manage publisher portal](https://marketplace.visualstudio.com/manage/publishers/colinsalmcorner).