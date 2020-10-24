# os1-lab-4-
Os1 Lab 4
Ex1
1.

2.
The value for count2 increases with different amounts using the signal kill -s SIGUSR1 <pid> and kill -s SIGUSR2 <pid>
kill -s SIGALRM <pid> returns the value of the counter in the moment is is executed not when the counter secondes output the valuethat  comes next

3.
with kill -s SIGTERM <pid>, the process is terminated but a final value is reterned.
with kill -s SIGKILL <pid>, the process is irrevercibly killed and a message killed is reterned to the terminal.

4. + 5.
SIGSTP or ctrl+z does not work on the counter
kill -s SIGSTOP temporarily stops the counters execution tahat can be later continued with kill -s SIGCONT
