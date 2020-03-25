The data source, technique and group YAML files can be edited using the [DeTT&CT Editor](https://rabobank-cdc.github.io/dettect-editor).

### How to run
The Editor is hosted on GitHub and can be found [here](https://rabobank-cdc.github.io/dettect-editor). In addition, the Editor can be run locally using the following command: `python dettect.py editor`. Hosting the Editor on your own webserver is possible by copying the content of the [`dist`](https://github.com/rabobank-cdc/DeTTECT/tree/master/editor/dist) directory to the root folder of the server.

### Technology stack
The Editor is created using the progressive JavaScript framework [Vue.js](https://vuejs.org/) and is entirely client-side. Therefore, the content of your YAML file is not send to a server.

### Limitations
With a few exceptions, all key-value pairs within a data source, techniques or group YAML file can be edited. More info can be found [here](Future-dev#dettct-editor).

Please note that comments (`#`) within your YAML files are not preserved due to lack of support in the YAML JavaScript library. Put your comments within a key-value pair to keep them. For example: `my-comment-1: your comment goes here`.
