# What is adb? 
According to https://developer.android.com/studio/command-line/adb adb is:

> Android Debug Bridge (adb) is a versatile command-line tool that lets you communicate with a device. The adb command facilitates a variety of device actions, such as installing and debugging apps, and it provides access to a Unix shell that you can use to run a variety of commands on a device. It is a client-server program that includes three components:
>
> * A client, which sends commands. The client runs on your development machine. You can invoke a client from a command-line terminal by issuing an adb command.
> * A daemon (adbd), which runs commands on a device. The daemon runs as a background process on each device.
> * A server, which manages communication between the client and the daemon. The server runs as a background process on your development machine.

We will use adb to communicate wirelessly with the robot controller to update the FTC code running on the robot. The link above contains a lot more information on adb and what you can do with it

# Utilities
The following scripts were put together to give you the convenient ways to do tasks without the need to type in multiple commands everytime you would like to complete a task

## adb_list.bat
A Windows script to list the devices connected to your adb server

## adb_start.bat
A Windows script to cleanly start the adb server and connect to the robot controller on the wifi network you are connected to

## adb_stop.bat
A Windows script to stop the adb server and connection to the robot controller
