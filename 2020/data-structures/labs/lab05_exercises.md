---
layout: page
course: "sbe201"
category: "lab"
year: "2020"
title:  "Lab 5: Doubly linked lists, classes, templates"
by: "Asem"
pdf: true
---

* TOC
{:toc}

## Initialize `lab05` files

### `wget`

You need to download the initial source files. `wget` program can help you in general to download files from the internet. In case you don't have it in your system you can install it using:

```bash
sudo apt install wget
```

### Download source files

Before downloading files, go to your lab repository and make `lab05` directory then go to the newly created folder:

```bash
mkdir lab05 # Execute in repo folder
cd lab05
```

There are **eight files** we need to download. However, we can first download a single text file that includes the links for the other 8 files.

```bash
wget https://raw.githubusercontent.com/sbme-tutorials/sbme-tutorials.github.io/master/2020/data-structures/snippets/lab05/linkedlists/download.txt
```

Now to download the **eight files** in a single command:

```bash
wget -i download.txt
```

Now if you list the files in the current directory you should see the following output:

<pre><font color="#8AE234"><b>asem@asem-pc</b></font>:<font color="#729FCF"><b>~/GP/sbe201-2020-labs-A-Alaa/lab05</b></font>$ ls
CMakeLists.txt  DLL2.hpp  download.txt   main_dll2.cpp  main_std.cpp
DLL1.hpp        DLL3.hpp  main_dll1.cpp  main_dll3.cpp
</pre>

From the QtCreator, open the current directory as a project by selecting `CMakeLists.txt` file.


<br>
<img src="qt1.png" style="width:60%">
<br>

<br>
<img src="qt2.png" style="width:60%">
<br>

<br>
<img src="qt3.png" style="width:60%">
<br>



## Application 1: remove duplicates from doubly linked list (procedural)

<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fsbme-tutorials%2Fsbme-tutorials.github.io%2Fblob%2Fmaster%2F2020%2Fdata-structures%2Fsnippets%2Flab05%2Flinkedlists%2Fmain_dll1.cpp&style=default&showBorder=on&showLineNumbers=on&showFileMeta=on"></script>

## Application 2: remove duplicates from doubly linked list (object)


## Application 3: remove duplicates from doubly linked list (object+template)

## Application 4: print COVID19 statistics (group by country)