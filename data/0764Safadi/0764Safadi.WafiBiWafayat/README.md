# Please, answer the following questions about the text that you work on

[[Last update Maxim: August 15, 2016]]
[[Last Update Jonas: Maerz 15 2017]]
 - started to work on the text again (Jonas)

Copy-paste these questions into the README.md file and answer them.

## 1. Describe why you chose this specific version of the text. Why others, in your opinion, are worse?

MGR: chose JK version; they are all identical; based on the same edition; formatted in the same manner, but JK has more tags already in place; I am under impression that Shamela and Shia versions are based on JK

## 2. Which edition you used for collation? How close the text to the edition? Is pagination the same?

Ahmad Arnaut / Turki Mustafa (metadata in each text file); texts is an exact reproduction of the edition, although structural elements are not always formatted; pagination is the same.

## 3. Have you noticed any typos? If yes, how many? (Guesstimate is fine)
Reproduction is very clean; I have not run into any typos, although there must be --- the book is almost 30 volumes.

JoK: Found for instance:الأمام instead of الإمام
حرث instead of حارث
وثلث ماية
PageV03P087 -> wrong page break
entry 185 او instead of ابو

+ many similar mistakes some as well in the headlines -> I did not correct them

## 4. Add any comments on the text

The formatting is quite messy; it will take a while to mARkdown this book ...
p


JoK:

THe work is secmented into two parts: The first one until the middle of volume 5 is not in alphabetical order. The second part starting afterwards is in alphabetical order. The first part took a lot of time, as is wasn't effectivly possible to use regular expressions and the formating was very messy, in the second part most entries are tagged correctly, but not a 100%.
Follwing I made an overview of the volumes I worked on

1V: 238/248 of names were marked -> all found
2V: (249 - 854) 357/606 -> all found
3V:(855-1455) (65/600) -> 9 missing
4V: (1456-1956)(493/500) -> 7 missing
5V: (1957-2353)(___ /396) 
new part (entries start from number 1 again:
(1-87) -> all found
6V: (87/599) (513/512) -> one entry too much - did some probes and the pdf and the tagged entries seemed to fit well overall
V7:(601-1062)(463/461)-> one entry to much - evrything else like same as V6
V8:(1063 - 1568) (506/505)-> one entry too much.
second half of the text checked in detail, in the first half there seemed to be very few misstakes only, so I just probed
V9:(1569-2113) (554/554)
as I found the correct number of entries I thought the quality would be good but in fact it was very messy - corrected quite some enties and headlines. Until page 238 it should be mostly alright now.

About the first part:
With regular expression I wrote everything can be found but -> entries that are
- wrongly not marked as new paragraph
- have a line break within the headline
- have speeling mistakes
- doesnt start at the beginning of the line

-some entries are found that are no headlines, mostly they begin with direct speech like
 قال او  سمع

-> all is due to unconsistancies in the text the amount of missing entries is ca 30% so I still have to check each entry on its own.


Some headlines were marked in the markdown file but not in the PDF. Still they fit the logic of the headlines of the text

example: 
### | ابن كرام 
### $ المجسم محمد بن  كرام


(^# \|)|(#3)|\w \$ 

JoK: page 62-96 V1 are missing
page 62 and 61 are missing therefore 6 biographies are not included
entrz 1461 is missing

JoK: stopped working on the text on the 07.04. after about 20 hours of work. I think it will take several more days or weeks to finish this text. It might be possible to use regex, but for me it was far too difficult, maybe everthing has to be done manualy.
