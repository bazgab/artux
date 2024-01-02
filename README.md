<div align="center">

<pre>
 █████╗ ██████╗ ████████╗██╗   ██╗██╗  ██╗
██╔══██╗██╔══██╗╚══██╔══╝██║   ██║╚██╗██╔╝
███████║██████╔╝   ██║   ██║   ██║ ╚███╔╝ 
██╔══██║██╔══██╗   ██║   ██║   ██║ ██╔██╗ 
██║  ██║██║  ██║   ██║   ╚██████╔╝██╔╝ ██╗
╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚═╝  ╚═╝
</pre>
</div>

A simple real-time CPU Temperature tracker for Unix-based systems. 

## Installation

Artux can be installed through PyPI for your terminal with the command:

```
pip install artux
```
Then we should cd into the directory and use the Poetry package manager to create a virtual environment and run the script:

```
poetry install
```

## Using Artux

To begin tracking, just type this command in the directory where the module is located: 
```
>>> poetry run artux
```
in the terminal, the program will start and you will be able to see each CPU Core's temperature along with fan speed (in RPM) and the battery charge (in case you're using a laptop, if not it should always indicate 100% coming from your PSU).

To exit the program, close the terminal window or press <kbd>Ctrl</kbd> + <kbd>C</kbd> for a keyboard interrupt.

## Showcase
![example](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNnlpb3hpMmZzNDNmbG5xOG1reDMwNzMzdGQyeGxtMHk3a3MzNzlxZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/gfZ2s0pmLtnbdTcgKL/giphy.gif)

## Contributing

Contributions are more than welcomed, a next step would be some work around to make the module more easily accessible globally. You can contact me directly over e-mail or create a PR and I will try my best to be quick on updates. 

