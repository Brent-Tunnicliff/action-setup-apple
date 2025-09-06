# action-setup-apple

Common apple pipeline setup I use for my projects.

## Outputs

* `destination.outputs.destination`: The destination value to pass into the xcodebuild command.
* `test_results_config.outputs.file_name`: The file name of the test results bundle. Dynamically generated based on the inputs provided.
* `test_results_config.outputs.path`: The full path of the test results bundle.
