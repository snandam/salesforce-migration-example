#### Sample workflow to retrieve and publish changes to salesforce org

- Copy build.properties.sample to build.properties
- Update values of sf.username, sf.password. If you have a personal token enabled put value of sf.token

#### To Retrieve source code from salesforce org

- Update src/package.xml with the list of components

```sh

ant retrieveCode

```

- To deploy contents in src

```sh

ant deployCode

```
