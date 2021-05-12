---
title: How to Use Fyodor
---
This is just a note on how to install and use Fyodor for Windows.

Source: [GitHub](https://github.com/rccavalcanti/fyodor)

**Table of Contents**
* TOC
{:toc}

## How to Install Fyodor
---
1. Install [Ruby](https://www.ruby-lang.org/en/).
2. Open using **Start Command Prompt with Ruby**.
3. Type ```gem install fyodor```


## How to Use Fyodor
---
1. Get the ```My Clippings.txt``` file from Kindle
2. Put it somewhere like ```C:\Users\USERNAME\Desktop\My Clips```
3. Open Ruby using **Start Command Prompt with Ruby**.
4. Type ```cd C:\Users\USERNAME\Desktop\My Clips``` to point the command prompt to that location where the ```My Clippings.txt``` file is located.
5. Type ```fyodor "My Clippings.txt"```
6. Wait for program to extract the text file and add a ```fyodor_output folder``` on the directory.


## How to Update Fyodor
---
1. Open using **Start Command Prompt with Ruby**.
2. Type ```gem update fyodor```