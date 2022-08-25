# Loops, conditions and parsing

Project done during **ALX Software Engineering Scholarship 2022** at **Alx Students Education**. It aims to learn about loops (`while`, `until` and `for`), condition statements (`if`, `else`, `elif` and `case`), shebangs and how to create SSH keys with **Bash**.

Not passing Shellcheck:
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/251/Vxotqyj.png" width="600px"/>

Passing Shellcheck:
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/251/ubHWxDU.png" width="400px"/>

## Resources
Read or watch:

* [Loops sample](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_09_01.html)
* [Variable assignment and arithmetic](https://tldp.org/LDP/abs/html/ops.html)
* [Comparison operators](https://tldp.org/LDP/abs/html/comparison-ops.html)
* [File test operators](https://tldp.org/LDP/abs/html/fto.html)
* [Make your scripts portable](https://www.cyberciti.biz/tips/finding-bash-perl-python-portably-using-env.html)
* [SSH Key Authentication | How to Create SSH Key Pairs](https://www.youtube.com/watch?v=33dEcCKGBO4)

## Technologies
* Scripts written in Bash 4.4.23(2)
* Tested on Ubuntu 20.04 LTS

## Files

| Filename | Description |
| -------- | ----------- |
| `0-RSA_public_key.pub` | File that stores a RSA public key to access servers via SSH |
| `1-for_best_school` | Displays `Best School` 10 times with a `for` loop |
| `2-while_best_school` | Displays `Best School` 10 times with a `while` loop |
| `3-until_best_school` | Displays `Best School` 10 times with an `until` loop |
| `4-if_9_say_hi` | Displays `Best School` 10 times and displays `Hi` for the 9th iteration |
| `5-4_bad_luck_8_is_your_chance` | Loops from 1 to 10 and displays `Best School`, except for 4th and 8th iteration which displays `bad luck` and `good luck`, respectively  |
| `6-superstitious_numbers` | Displays numbers from 1 to 20 and displays `bad luck from China`, `bad luck from Japan` and `bad luck from Italy` for the 4th, 9th and 17th iteration, respectively |
| `7-clock` | Displays the time for 12 hours and 59 minutes |
| `8-for_ls` | Displays the content of the current directory in a list format |
| `9-to_file_or_not_to_file` | Gives information about the `school` file |
| `10-fizzbuzz` | Displays the `fizzbuzz` sequence |
| `100-read_and_cut` | Displays the content of the file `/etc/passwd` |
| `101-tell_the_story_of_passwd` | Displays the content of the file `/etc/passwd` with an specific message |
| `102-lets_parse_apache_logs` | Displays the visitor IP along with the HTTP status code from an Apache log file |
| `103-dig_the-data` | Groups visitors by IP and HTTP status code and displays the occurrences, from the greatest to the lowest number |
