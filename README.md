# action-setup-apple

Common apple pipeline setup I use for my projects.

## Outputs

* `destination`: The destination value to pass into the xcodebuild command.
* `test_result_file_name`: The file name of the test results bundle. Dynamically generated based on the inputs provided.
* `test_result_path`: The full path of the test results bundle.
