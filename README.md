# Logtalk Extension Pack

Recommended extensions for [Logtalk](https://logtalk.org) development.

## Included extensions

Installing this pack automatically installs the following extensions:

- [Logtalk for VSCode](https://marketplace.visualstudio.com/items?itemName=LogtalkDotOrg.logtalk-for-vscode) (language support)
- [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server) (preview of generated documentation and diagrams)
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) (notebook development)
- [Allure Support](https://marketplace.visualstudio.com/items?itemName=qameta.allure-vscode) (browsing test results)

Writing and running Jupyter notebooks also requires installing the Logtalk kernel, available from PyPI and Conda registries:

- <https://pypi.org/project/logtalk-jupyter-kernel>
- <https://anaconda.org/conda-forge/logtalk-jupyter-kernel>

To generate Allure test reports, edit the VSCode Logtalk settings to include `-f xunit` in the arguments of the `logtalk_tester` script, select the command "Logtalk: Run Project Testers" in the VSCode Explorer pane by control-clicking in a Logtalk source file, run the `logtalk_allure_report -p` shell command in the VSCode terminal (in the project directory), and then select the command "Allure Report: serve test results" in the VSCode Explorer pane by control-clicking in the `allure-results` folder.

## Contributions

For contributions to the individual extensions, please see their documentation.

For suggestions on additional extensions to include in this pack, [open an issue in this pack repository](https://github.com/LogtalkDotOrg/logtalk-extension-pack.git).

## License

[MIT](https://github.com/LogtalkDotOrg/logtalk-extension-pack/blob/master/LICENSE)
