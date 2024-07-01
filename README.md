# Ascii-art

## Description

Ascii-art is a program which consists in receiving a string as an argument and outputting the string in a graphic representation using ASCII. Time to write big.

What we mean by a graphic representation using ASCII, is to write the string received using ASCII characters, as you can see in the example below:

```
@@@@@@BB@@@@``^^``^^``@@BB$$@@BB$$
@@%%$$$$^^^^WW&&8888&&^^""BBBB@@@@
@@@@@@""WW8888&&WW888888WW``@@@@$$
BB$$``&&&&WWWW8888&&&&8888&&``@@@@
$$``&&WW88&&88&&&&8888&&88WW88``$$
@@""&&&&&&&&88888888&&&&&&88&&``$$
``````^^``^^^^^^````""^^``^^``^^``
""WW^^@@@@^^``````^^BB@@^^``^^&&``
^^&&^^@@````^^``&&``@@````^^^^&&``
``WW&&^^""``^^WW&&&&""``^^^^&&88``
^^8888&&&&&&WW88&&88WW&&&&88&&WW``
@@``&&88888888WW&&WW88&&88WW88^^$$
@@""88&&&&&&&&888888&&``^^&&88``$$
@@@@^^&&&&&&""``^^^^^^8888&&^^@@@@
@@@@@@^^888888&&88&&&&MM88^^BB$$$$
@@@@@@BB````&&&&&&&&88""``BB@@BB$$
$$@@$$$$$$$$``````````@@$$@@$$$$$$
```

## Usage

To use this program you need to clone this repo : 
```
git clone https://zone01normandie.org/git/dbourcie/ascii-art.git
```
Then you have to run it by executing this command line : 
```
go run . <Your text here> <style>
```
You can chose the *style* of the output between *standard*, *shadow* and *thinkertoy* whith the selector. By default, if you don't write any style it will output in *standard* style.

What looks like the different styles :
```
 Standard          Shadow          Thinkertoy

    /\              _|_|              O   
   /  \           _|    _|           / \  
  / /\ \          _|_|_|_|          o---o 
 / ____ \         _|    _|          |   | 
/_/    \_\        _|    _|          o   o 
 ```                 

And it will output your string in a graphic representation using ASCII

## Author

```
Dylan,Daro,Alex.

