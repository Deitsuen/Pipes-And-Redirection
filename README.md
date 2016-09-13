# Pipes-And-Redirection
$ cat ex12.txt ex13.txt | less
$ cat < ex13.txt
1
2
3
4
$ less < ex12.txt
$ less < ex12.txt | cat | less
$ cat ex13.txt > ex15.txt
$ cat ex15.txt
1
2
3
4
$


> cd ..
> cd temp
> cat ex12.txt,ex13.txt | more
a
b
c
d
1
2
3
4
> echo "I am a new file." > ex15.txt
> cat ex15.txt
I am a new file.
> cat ex15.txt > another.txt
> cat another.txt
I am a new file.
> cat ex15.txt | more
