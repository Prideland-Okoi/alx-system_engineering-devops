# Processes and signals

Project done during **ALX Software Engineering Scholarship 2022** at **Alx Students Education**. It aims to learn about PID, processes and commands that handles them (`ps`, `pgrep`, `pkill`, `kill`, etc) in **Bash**.

<img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/d8ecfe9109334898b9540ffd20cf64d1c06f0c09.jpg" width="400px"/>

## Resources
Read or watch:
* [Linux PID](http://www.linfo.org/pid.html)
* [Linux process](https://www.thegeekstuff.com/2012/03/linux-processes-environment/)
* [Linux signal](https://www.thegeekstuff.com/2012/03/linux-signals-fundamentals/)

## Technologies
* Scripts written in Bash 4.3.11(1)
* Tested on Ubuntu 14.04 LTS

<img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/37975393ead381f4d27f268f7337c6d3013b4991.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220820%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220820T003701Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=99389a4ef38ca3c5425485f21a2bcc59fc8b147ed766cfeab7d8066e4b11d4e5" width="300px"/>

## Files

| Filename | Description |
| -------- | ----------- |
| `0-what-is-my-pid` | Displays its own PID |
| `1-list_your_processes` | Displays a list of currently running processes |
| `2-show_your_bash_pid` | Displays lines containing the `bash` word in a list of currently running processes |
| `3-show_your_bash_pid_made_easy` | Displays the PID, along with the process name, of processes whose name contain the word `Bash` |
| `4-to_infinity_and_beyond` | Displays `To infinity and beyond` indefinitely |
| `5-dont_stop_me_now` | Kills `4-to_infinity_and_beyond` process |
| `6-stop_me_if_you_can` | Kills `4-to_infinity_and_beyond` process |
| `7-highlander` | Displays `To infinity and beyond` indefinitely and displays `I am invincible!!!` when receiving a `SIGTERM` signal |
| `8-beheaded_process` | Kills the process `7-highlander` |
| `100-process_and_pid_file` | Prints some messages according to sent signals |
| `101-manage_my_process` | Init script that manages `manage_my_process` with `start`, `stop` and `restart` instructions |
| `102-zombie.c` | C program that creates 5 zombie processes |
