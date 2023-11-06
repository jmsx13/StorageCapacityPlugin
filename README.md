# CEA's Storage Capacity Plugin

A plugin for the City Energy Analyst to evaluate the benefits of storage electricity, heat and hydrogen taking advantage of the solar potential in a building.

To install this plugin, open CEA console and enter the following command to install the plugin to CEA:

  ```pip install -e PATH_OF_PLUGIN_FOLDER```

(NOTE: PATH_OF_PLUGIN_FOLDER would be the DESIRED_PATH + 'cea-storage-capacity')

Next, enter the following command to enable the plugin in CEA:

  ```cea-config write --general:plugins cea_storage_capacity.storage_capacity.StorageCapacityPlugin```

Now you should be able to enter the following command to run the plugin:

  ```cea storage-capacity```
