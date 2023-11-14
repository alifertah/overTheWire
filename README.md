# overTheWireSolves

<details>
<summary >level 0</summary>


> first of all you need to connect to ssh and this step must be repeated everytime you get the password of the next level

```sh
ssh [username]@bandit.labs.overthewire.org -p 2220
// this will ask you to enter the password
```
once you get there type ```ls``` you will find a file called ```readme```
- type :
```sh
cat readme
```

this will show you the password to the next level 
- now type ```exit``` to exit this machine and connect to the level2 machine
</details>

<details>

<summary>level 1</summary>

> connect to this machine using ssh as mentionned before

once you get there type ```ls``` you will find a file called ```-``` 
if you try to ```cat - ``` this wont work because '-' is a special character that used to indcates flags of a command so if you wanna tell the terminal to give you tha content of that '-' file, type :

```sh
cat ./-
```

</details>