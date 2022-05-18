# detab
*A python script to turn tabs into spaces the right way.*
<br><br>

<h4 align="center">detab turns all tabs into spaces, not just leading tabs.</h4>
<p align="center">  
  <img width="772" src="https://i.imgur.com/CvZqvU7.png">
</p>
<br>

<h4 align="center">Not all tabs have the same length, detab replaces each one by the right amount of spaces.</h4>
<p align="center">  
  <img width="772" src="https://i.imgur.com/3J0YN9t.png">
</p>
<br>

<h4 align="center">The tab size is configurable, but it defaults to 4 if not specified.</h4>
<p align="center">  
  <img width="772" src="https://i.imgur.com/DAiMHj1.png">
</p>
<br>

## Why?
Spaces are the way to go for most programming languages according to coding style rules. Tabs do not measure the same across the whole document as their length varies according to the position of the character in the line. Their size also depends on the configuration of the text editor used, which makes them inconsistent. However, the tab key can be configured to insert spaces instead of tabs on some editors to save time and keystrokes, which is an option I recommend.

There are some solutions out there to replace tabs with spaces, but they often only take into account leading tabs and replace them with a fixed amount of spaces. detab goes one step further, allowing you to easily make the transition from tabs to spaces over long and complex files and replacing all of them accurately to maintain the original look of the document.
<br><br>

## Installation
The following commands will download the latest version of detab from this repository 
and install it in your `/usr/bin/` directory:
```
git clone https://github.com/Julynx/detab
cd detab
```
```
chmod +x detab
```
```
sudo cp detab /usr/bin/
```
The program can now be ran from a terminal with the command `detab`.
<br><br>

## Usage
The following command will **REPLACE** all tabs in the specified file with spaces:
```
detab <filename> [tabsize] - Defaults to 4
```
It has been tested with Python 3.8.10, results may vary if other python versions are used.
<br>
