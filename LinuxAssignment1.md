## **LINUX Assignment 1**<a id="linux-assignment-1"></a>

Before jumping into the most-used Linux commands, make sure to fire up a **terminal**. In most Linux distributions, you would use Ctrl + Alt + T to do so. If this isn’t working, search in your application panel for “terminal.”

## 1:-How to make a directory.

****`mkdir` **Command**

****To create folders in the shell, you use the `mkdir` command. Just specify the 

new folder’s name, ensure it doesn’t exist, and you’re ready to go.

For example, to make a directory to keep all of your images , just type:

```
mkdir images/
```
![](https://lh7-us.googleusercontent.com/JypaBG-IZ6PTrkXXHk8TKvtLotsV92iiC5kWOl1NL8fLJ03FrU4CXyapU1dd5Pa_ub1fDPOTbl3aj7qQsh14e33_q47EHFyAt5sCuUOPgEUhv0-twO10W10_P7gH3AuJqQSyxfxhYemOqxrCAI8odCk)****

##To create subdirectories with a simple command, use the parent (**`-p`**) flag:

```
mkdir -p movies/2004/
```
![](https://lh7-us.googleusercontent.com/N1sT9iXAl2OOuyQCvLVm5BiEwm6RrYeRngaIvRc77O-NiG5yRyqHTBQJMCeucaYfoZF60iOvslK23WZXXiCZKHfyRbVCHjKz4rCV03eumXbfTGEz9rOtzQhZu5vOarX15hrUfuma7OYnJL_mRcjXrrw)****

\
\


## 2:-Remove a directory.

To permanently remove a directory in Linux, use either the rmdir or rm command. The **rmdir** or **rm -d** command is for removing empty directories, while the **rm -r** command deletes non-empty directories.
```
rmdir images/
```

![](https://lh7-us.googleusercontent.com/yseWwmqUhfUYhGI5bBZkP5yJlLFx4EJkp-Ae7YEhnM8wwwwE_hAgFPbTV-1nvsMQ85EVUnYz2FIAvbMCtF8tquNb972vp1yTRnBSw-cJXUXL_7PDoZJlPTcsy9eLJ9JlaIr_TzFy0LwiYGnDUF_nO3s)

## 3:-Make a copy of a file.

****To make a copy of a file in Linux, you can use the **cp** command. Here's 
the basic syntax:

```
cp source\_file destination
```

![](https://lh7-us.googleusercontent.com/SGiiRuKObrhah3fleVyeqcpkImpFQzy1vvt2PCSQDdkpL2-w2Gihok0ednLWCjbMB6UvA7RnK1i6Fic_drmwBVnTo0V3LSffXXZP3bSs6ahAx3xJOkOk9oj7kL3XHPI-SEOr6kyrjD-cGry09oYwKwA)****

\


## 4:-Move or rename a file.

****To move or rename a file in Linux, you can use the **** **mv** command. Here's 

the basic syntax:

```
mv source\_file destination
```

![](https://lh7-us.googleusercontent.com/khrcipy270coludVpFfhM5Ykf_CRQuy3gam9YIzeSToam8zlcaqEtO4q7QXtvuh3MFuQ7V5gr8FcU3MQcFlORACEiBLzUsy86VKK7uDI7be63xwII1tmyf8zhElyHDQDBKn7hR8_zaqBdZQNGSgU850)****

     ****

## Rename a file:.

**mv old\_filename new\_filename**

![](https://lh7-us.googleusercontent.com/ejzZvtr-7QnoVDKHuhScBH0nSlMRJZkl5_8O9mhwYB-rivaxKM0NSJuWsIR5U4KK8n_GJEEUbL2qRnpefVluVxxcKzBl0LVYc4fNTraPT33a0AY5hrI_WbNNrgxFtLvUE2IipnhmZ6B-wCxbDWCvHsY)****

\
\
\


## 5:-Create an empty file.

****To create an empty file in Linux, you can use the **touch** command. Here's

the basic syntax:

```
touch filename
```

****For example, if you want to create an empty file named `example.txt`, 
you would run:

![](https://lh7-us.googleusercontent.com/XBpNQbzEcNpZjIt43cWOVSt7GN1G0q08bvIBUZEzxNkNn3-SK5FCU3iG2f6M3USZyHT6BF9rd7oEcewIhcqHY4aj1KwFJXDJ3QXeZMvzaZanargvxQ1z75KAMsLffl8K9IxLYD22orIL2bobFH5j0B8)

 ****

## 6:-Remove multiple files with a single command

****To remove multiple files with a single command in Linux, you can use the **rm** **** 

command followed by the names of the files you want to delete. Here's the 

basic syntax:

```
rm file1 file2 file3
```

![](https://lh7-us.googleusercontent.com/8Oz7x_k2nKEaN3Wra9WPIQhLfe9V7rIA4J1X9jTy5Eeb6oJzvG6Z_AHFKEg-UPBO95MKWZTcLNz7MRlfdgScctOVfDfbo_4JWq0g8KKSW--Xfyk-KuTaUP9RnRjvEw3P74K87MANRgLlBgNdXAf16Lk)****

\


## 7:- Remove content from the folder without removing folder.

To remove the contents of a folder without removing the folder itself in Linux, you can use the **rm** command with the **-r** (recursive) Here's an example:

```
rm -r file1 file2 file3
```

![](https://lh7-us.googleusercontent.com/uKeQVe-97Hu1iWgH7F3lN8CszPldezvyNLTwUJB-lglTWl_ALPp2_jCCsespbeU9U3nIbiTdRqJHHNISFX85aADmJKsNrTqVXJK1a3nBoU2nZOKYYC3vDQ7hEfvA9ngsyTb8KTZIWeKHus9LkbaW5yo)****

\


## 8:- Create multiple folder(a-z) with a single command.

**Use command.** To create multiple folders(a-z) with a single command.

```
mkdir {a..z}
```

![](https://lh7-us.googleusercontent.com/wsevoGOTaDgFQzklbLsbHIk9jtLAwTZr2aXwzb7JSJu6W2Ipwc0qZOX8l6-660PhH2L1TF1zyadOZ4-VKnnisOhZnos4AXO5EPkDwV8r7FN5tbn2vBlaK2MwRTIPt33OsyjICRuGYSgPCyQ2hU9b8Uo)
