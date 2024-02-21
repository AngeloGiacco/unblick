# Unblick

The key idea is to enable a workflow around the following

setup: 
0. a. the user points to an unstructured file, probably json
0. b. the json is loaded into a rumbledb instance

query workflow:

1. Receive a natural language prompt
2. Translate the prompt into jsoniq code 
3. execute the jsoniq code in some rumbledb instance
4. return the results back to the user
