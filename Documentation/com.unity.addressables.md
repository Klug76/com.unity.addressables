# Unity Addressables

Our new Addressable Asset System allows the developer to ask for an asset via its address and get back the thing that resides at that address. Once an asset (e.g. a prefab) is marked "addressable", it generates an address which can be called from anywhere. Wherever the asset resides (local or remote), the system will locate it and its dependencies, then return it.

The Addressable Asset System uses asynchronous loading to support loading from any location with any collection of dependencies. Whether you are using direct references, traditional asset bundles, or Resource folders, addressable assets provide a simpler way to make your game more dynamic. The Addressable Asset System  simultaneously opens up the world of asset bundles while managing all the complexity.
