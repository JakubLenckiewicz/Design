---

views:
    redovisa:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa

    mig:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-mig
---

Test
=========
Text
---------
Detta här **innehåll** är *skrivet* i markdown och du hittar innehållet i filen `content/test.md`

### Header 3

>## Links
>
>This is a blockqute.

### My favorite things

*   Friends

    And I can't wait too visit my Swedish friend that lives in Australia.

*   Family
*   Food
*   Games
*   Sport

### My favorite colors

1.  Blue
2.  Red
3.  Yellow  

This is a [link](https://youtube.com/ "Youtube")

I use [Youtube][1] more than any other social media, you name it [Facebook][2], [Instagram][3], [Twitter][4] or [Tik Tok][5]

[1]: https://youtube.com/ "Youtube"
[2]: https://facebook.com/ "Facebook"
[3]: https://instagram.com/ "Instagram"
[4]: https://twitter.com/ "Twitter"
[5]: https://tiktok.com/ "Tik Tok"

![Bild](image/theme/vector.png?width=40% "Title")
