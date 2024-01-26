# test_ddm
Shell-script to test the Distict Descriptor Mode in Onionbalance using docker containers

Before running you need to set a few parameters:
- NUMBER_INSTANCES
- NUMBER_CLIENTS
- HOST_DIR

Change the used repository / branch as needed.
The script automatically creates and runs all needed files and containers.
There is a file created to track which backend instances where called: $HOST_DIR/clients/all.log

After running the script, all images and containers need to be romoved manually.
