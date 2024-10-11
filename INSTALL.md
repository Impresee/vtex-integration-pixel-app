# Installation process

The app needs to be installed via the [VTEX IO CLI](https://developers.vtex.com/docs/guides/vtex-io-documentation-vtex-io-cli-install)
Then follow these steps:

1. Clone this app [github repository](https://github.com/Impresee/vtex-integration-pixel-app)
2. Navigate to the app repository `cd /.../vtex-integration-pixel-app`
3. Login into the store's account `vtex login {storeAccount}`
4. Change the vendor in `manifest.json` to the name of the store
5. Publish the app `vtex publish`
6. Install the app `vtex install`

You can now leave the app repository.
To configure the app go to the VTEX admin and then:

1. Navigate to Apps > App Management
2. Find the app **Impresee Script Integration App**, and click on it.
3. Put the name of the store in the **Impresee script name** field
4. Click on **Save**
