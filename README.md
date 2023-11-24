## Description
Small, bash-only, interactive script using the 'kill' builtin that allows 
for sending signals to processes matched against a given regex pattern. 
Just as well, you may list the environment of the matching/selected processes. 

## Usage
Simply make `Kill` executable with `chmod +x Kill` place it in you path, and 
run `Kill`. Optionally you may specify a sigspec with `-s sigspec` or a signum
with `-n signum` (the default sigspec/signum is the standard SIGTERM/15).
A starting pattern may be specified `-p <pattern>`. Note, if you do not specify a
pattern, you will be prompted for one. 

Once the program is running and you are in the 'Process selection' menu, you may type
'help' and enter to see a full list of available options.
