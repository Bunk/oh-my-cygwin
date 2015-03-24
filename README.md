# OH MY CYGWIN

Looking for a real Terminal for Windows?
Relax you just found it. This sets up a working ZSH Shell powered by [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) and the [apt-cyg](http://code.google.com/p/apt-cyg/) package manager.

I took care of installing and configuring some packages so that you have vim, git and ssh just one keystroke away.

# Setup

Install [cygwin](http://www.cygwin.com/) with __wget__ and __git__.

Create a cygwin passwd file (cygwin doesn't use one for user management, so you need to create it to change the default shell)

    mkpasswd -l >/etc/passwd

Then start cygwin and execute

    wget --no-check-certificate https://raw.github.com/bunk/oh-my-cygwin/master/oh-my-cygwin.sh -O - | sh

Restart cygwin, et voila!
Your windows Terminal will look like this

![oh-my](https://coderwall-assets-0.s3.amazonaws.com/uploads/picture/file/1297/oh-my-cygwin.PNG "OH-MY-OH-MY")
