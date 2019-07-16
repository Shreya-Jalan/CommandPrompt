# CommandPrompt
implementation of shell using C language

INTRODUCTION


Simply put, a shell program (sometimes called a shell script) is a text
file that contains standard UNIX and shell commands. Each line in a
shell program contains a single UNIX command exactly as if you had
typed them in yourself. The difference is that you can execute all the
commands in a shell program simply by running the shell program
(rather than typing all the commands within). Shell programs are
interpreted and not compiled programs. This means when you run a
shell program a child shell is started. This child shell reads each line
in the shell program and carries out the command on that line. When
it has read all the commands the child shell finishes.


PROJECT SCOPE


Shell script usage has not reduced instead increased over the years.
Most of the middleware tools such as ETL, MB etc are installed in
UNIX servers. To maintain those servers, pre-processing file , log
collection and performance improvement shell scripts are used. In this
project we are using C coding to implement some of the features
present in a typical shell such as arithmetic operation, viewing
history, etc.
