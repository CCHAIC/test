# test

## Overview
The goal of this program was to count the frequency of each alphabet letter (a-z, total 26 case insensitive) and five special characters (‘.’, ‘,’, ‘:’, ‘;’ and ‘!’) in all the .txt files under a given directory. 
alphabetcount.c is to count the frequency of alphabet letters, while specialcharcount.c is to count the frequency of the 5 special characters. 

## How to run the code
Calling the makefile and running "make testalphabet"/"make testspecial" will generate the executable file.
```
make testalphabet
make testspecial
```
Run the testalphabet program to count frequency of alphabet letters, the result will be stored in the file result.txt under result folder.
```
./testalphabet
```
Run the testspecial program to count frequency of special characgters, the result will be stored in the file specialresult.txt under result folder.
```
./testspecial
```

## test result for the given data folder
```
a -> 2973036
b -> 556908
c -> 765864
d -> 1786752
e -> 4883076
f -> 765336
g -> 809292
h -> 2818068
i -> 2586276
j -> 35112
k -> 401412
l -> 1728276
m -> 1050852
n -> 2509320
o -> 2766192
p -> 562848
q -> 28776
r -> 2177076
s -> 2465496
t -> 3291684
u -> 1015608
v -> 276804
w -> 1085040
x -> 46860
y -> 730752
z -> 12936

, -> 745668
. -> 798072
: -> 15708
; -> 32340
! -> 63228
```
