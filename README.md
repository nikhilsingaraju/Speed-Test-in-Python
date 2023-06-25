# Speed-Test-in-Python

This program is designed to measure the internet speed of your network connection using the speedtest-cli library. The speedtest-cli library is a command-line tool that performs internet speed tests by connecting to a nearby server and measuring the download and upload speeds.

The program begins by installing the speedtest-cli library using the `!pip install speedtest-cli` command. After that, it imports the necessary modules, including the subprocess module for running command-line commands.

The `internet_speed_test` function is defined to execute the speedtest-cli command and retrieve the download and upload speeds from the command output. The `subprocess.run` function is used to run the command, and the `capture_output=True` parameter is set to capture the command's output. The `text=True` parameter ensures that the output is returned as a string.

The command output is then processed to extract the download and upload speeds. The output is split into lines, and the relevant information is extracted using indexing and string splitting. The download and upload speeds are converted to floating-point numbers for further formatting.

Finally, the results are printed to the console, displaying the download and upload speeds in Mbps (megabits per second).

Overall, this program provides a simple and convenient way to measure and display the internet speed of your network connection using the speedtest-cli library.
