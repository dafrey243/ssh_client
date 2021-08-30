# ssh_client
SSH client to login to many devices to execute one or many CLI commands. Two files are need to be installed in the same directory. The first file is config_file.txt contains the CLI commands to issue to all the device IP addresses located in sshclient.py file. If using on Cisco devices the python script assumes you are logging in as priv 15. If user is less than 15 add the "enable" command followed by the enable_password as the first two lines in the config_file.txt file.
Running script example:

[dafrey@CrashCart functions]$ python sshclient.py 
