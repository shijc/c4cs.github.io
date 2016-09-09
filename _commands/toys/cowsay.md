---
---

cowsay
-------

`cowsay` is a program which generates ASCII pictures of a cow with a message.  The cow is also able to think using `cowthink`.

~~~ bash
$ cowsay "Hello World Moo~~~~~~"
 _______________________
< Hello World Moo~~~~~~ >
 -----------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
~~~

<!--more-->
It can also generate pictures using pre-made images of other animals, such as Tux the Penguin.

### Useful Options / Examples

#### Install

##### apt-get
~~~ bash
$ sudo apt-get install cowsay
~~~

##### Homebrew
~~~ bash
$ brew install cowsay
~~~

#### `Cowthink` Usage
~~~ bash
$ cowthink "What?"
 _______
( What? )
 -------
        o   ^__^
         o  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
~~~

#### -f Option
~~~ bash
$ cowsay -f tux "hi"
 ____
< hi >
 ----
   \
    \
        .--.
       |o_o |
       |:_/ |
      //   \ \
     (|     | )
    /'\_   _/`\
    \___)=(___/
~~~
The -f option specifies a particular cow picture file (``cowfile'') to use.  If the cowfile spec contains '/' then it will be interpreted as a path  relative to the current directory. Otherwise, cowsay will search the path specified in the COWPATH environment variable. To  list  all cowfiles on the current COWPATH, invoke cowsay with the -l switch (listed below).

#### -l Option
~~~ bash
$ cowsay -l
Cow files in /usr/local/Cellar/cowsay/3.03/share/cows:
beavis.zen bong bud-frogs bunny cheese cower daemon default dragon
dragon-and-cow elephant elephant-in-snake eyes flaming-sheep ghostbusters
head-in hellokitty kiss kitty koala kosh luke-koala meow milk moofasa moose
mutilated ren satanic sheep skeleton small sodomized stegosaurus stimpy
supermilker surgery telebears three-eyes turkey turtle tux udder vader
vader-koala www
~~~
These are the options we can use.

#### Other Cow Modes -b/g/p/s/t/w/y
~~~ bash
cowsay -g "I am a greedy cow"
 ___________________
< I am a greedy cow >
 -------------------
        \   ^__^
         \  ($$)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
~~~
There are several provided modes which change the appearance of the cow depending on its particular emotional/physical state.   The  -b  option initiates  Borg  mode;  -d  causes  the  cow to appear dead; -g invokes greedy mode; -p causes a state of paranoia to come  over  the  cow;  -s makes  the  cow  appear thoroughly stoned; -t yields a tired cow; -w is somewhat the opposite of -t, and initiates wired mode; -y brings on the cow's youthful appearance.

#### Finally, play around it and HAVE FUN!