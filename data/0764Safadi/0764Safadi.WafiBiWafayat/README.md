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

1V: 238/248 of names were marked -> all found
2V: (249 - 854) 357/606 -> all found
3V:(855-1455) (65/600) -> 9 missing
4V: (1456-1956)(493/500) -> 7 missing
4V: 2353 finished
new part: until entry 60 (page 224) 

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
