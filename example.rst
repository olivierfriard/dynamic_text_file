============
title
============


Example of content generated by an embedded Python script 
===============================================================


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

and now the following content is generated by a **Python script**! (see the code to visualize the Python code):

..  BEGIN_CODE TAG=01 LANG=python

    print('Hello world!')
    a = 1
    b = 2
    print(f"{a=}")
    print(f"{b=}")
    print(f"{a + b=}")
    # comment
    print()
    for i in range(10):
        print(f"{i}^2 = {i**2}")

..  END_CODE

.. BEGIN_OUTPUT TAG=01

| Hello world!
| a=1
| b=2
| a + b=3
| 
| 0^2 = 0
| 1^2 = 1
| 2^2 = 4
| 3^2 = 9
| 4^2 = 16
| 5^2 = 25
| 6^2 = 36
| 7^2 = 49
| 8^2 = 64
| 9^2 = 81

.. END_OUTPUT

End of the script generated content!

Usefull isn't it?



Exemple of content generated by an embedded bash script
=============================================================


blah blah blah ...


..  BEGIN_CODE TAG=bash LANG=bash
    date
    uptime
    cowsay 'Ciao!'
..  END_CODE


An embedded bash command has generated the following content (see the code to visualize the bash commands):

.. BEGIN_OUTPUT TAG=bash

| mer 10 mag 2023, 16:18:37, CEST
|  16:18:37 up 19 days, 22:18,  1 user,  load average: 0.26, 0.33, 0.51
|  _______
| < Ciao! >
|  -------
|         \   ^__^
|          \  (oo)\_______
|             (__)\       )\/\
|                 ||----w |
|                 ||     ||

.. END_OUTPUT
