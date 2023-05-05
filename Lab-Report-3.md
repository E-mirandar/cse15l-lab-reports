# LAB Report 3

Out of all the 3 different command given, I found the **less** command one of the more interesting ones to look up and research on

Within my research I was able to find 4 other alternates of the command **less** Which are shown here

- More 
- Head 
- Tail
- nl

---

## Alternate ways to use Less without using the command Less

### More

You might be wondering, what does the keywords More do? Well like less it does output the text within a file, but in a different way. Such as by pressing a certain keybind the text will scroll a certain percentage or backwards. It will always print out the whole text within a file but through a progressive way.

Example 1:
Here is how you can call it on one of the files in the technical directory:
```
more stringsearch-data/technical/911report/chapter-1.txt
```
<morebegining>

As we can see we can see only a small portion of the larger text, if we press f, it allows us to go forward a small percentage this is shown below, also if you press s or d, you can go forward a smaller percentage, th

<moreGoingForward>

If you press B on your keyboard you go backwards:

<moregoingbackwards>

Example 2
Another interesting way you can use more is by being explicit with how many lines you want to go forwards in
```
    more -100 stringsearch-data/technical/911report/chapter-1.txt
```

Here I emphasized that I should move forward in the text ever 100 lines, which makes going through the text a lot faster since it skips every 100 lines

<moregoing100>

---
### Head

Head shows the beginning portion of a file

Example 3
Head is pretty interesting since what it does is it shows the top portion of text in the given file as such:
```
head stringsearch-data/technical/plos/journal/plos/journal.pbio.0030021.txt
```
<Head1>

Example 4
Something I also found very interesting was that you can show out the amount of bytes in a file as shown:
```
head -c 3k stringsearch-data/technical/plos/journal.pbio.0030021.txt
```
<Head3kbytes>

these are the first 3 thousand bytes of the file which could be potentially useful?
---

### Tail

Tail is similar to head where instead of showing the beginning portion of the file, it shows the last portion of the file.







