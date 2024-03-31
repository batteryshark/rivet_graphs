# Mario's Rivet Graph Repository (RGR)
Some useful Rivet Graphs I've built to do stuff


## Graphs

* batch_runner: Executes a given graph in parallel with n max workers simulataneously until the queue is completed. Should be replaced by the "Iterator" node on Rivet 1.7.9

* clean_json: Parses code block or otherwise malformed json code and attempts to return a valid json object.

* config_loader: Given a path to a file in 'dotenv' format, read variables and set them as globals.

* macos_popup: Uses shell execution to create a MacOS notification popup (UNSAFE - Requires 'Node' runner)

* path_exists: Uses shell execution to test if a given filesystem path exists (UNSAFE - Requires 'Node' runner)
  
* run_python_code: Executes input python script and prints "result" variable, returns output. (UNSAFE - Requires 'Node' runner and Python plugin)

