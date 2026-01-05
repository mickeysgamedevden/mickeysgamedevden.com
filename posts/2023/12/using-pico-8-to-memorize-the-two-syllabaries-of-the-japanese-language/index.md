---
title: "Using PICO-8 to memorize the two syllabaries of the Japanese language"
date: 2023-12-17
categories: 
  - "pico-8"
tags: 
  - "japanese"
  - "japanese-language"
  - "language-learning"
  - "pico-8"
---

The code editor of PICO-8 has built-in support for hiragana and katakana characters, available in the P8SCII character set (characters 154 to 253).  

![The P8SCII characters 154 to 253](mickeysgamedevden.com/posts/2023/12/using-pico-8-to-memorize-the-two-syllabaries-of-the-japanese-language/images/image.png)

Available are the 46 basic hiragana and katakana characters, support for 25 dakuten and han-dakuten (created with ?and ?as [P8SCII decoration character](#lexaloffle)), and the 36 combination characters with small versions of the characters YA, YU & YO (?,?,?). Katakana dakuten/han-dakuten and combination characters built with small versions of A, I, U, E, and O as well as VU are not available, but could be built manually with decoration characters, albeit only with the available versions of the katakana vowels (unless one would like to create the missing characters as [one-off characters](#lexaloffle)). 

Within these constraints, I built KANAGRID, a simple tool to memorize the two syllabaries of the Japanese language (hiragana and katakana). 

![KANAGRID main view](mickeysgamedevden.com/posts/2023/12/using-pico-8-to-memorize-the-two-syllabaries-of-the-japanese-language/images/image-2.png)

Pressing ENTER shows the menu to change the current level (1-11), switch to hiragana or to katakana mode, or show the controls. An already known character is validated by pressing the ?(Y/Z)-key. ?(X) shows how the current kana is pronounced. If a controller is used, these two keys are mapped to the controller buttons 1 and 2. 

There are 11 levels, level 1 to 10 corresponds to the ten columns in which the kana are usually presented (A-KA-SA-TA-NA-HA-MA-YA-RA-WA). The final level 11 lets the user train sets of all 46 basic hiragana or katakana characters. The current level is automatically increased after validating several times that a kana is already known. Since not all katakana dakuten/han-dakuten and combination characters are available in PICO-8, KANAGRID is limited to the basic characters only. 

![The basic hiragana and katakana characters](mickeysgamedevden.com/posts/2023/12/using-pico-8-to-memorize-the-two-syllabaries-of-the-japanese-language/images/image-1.png)

Unfortunately, the built-in font of the PICO-8 platform is small, and some characters are difficult to recognize at first glance. I advise using a hiragana and a katakana chart in the beginning. I like the charts available at [Tofugu](#tofugu).

KANAGRID is available at [itch.io](https://maeschba.itch.io/kanagrid) and at [the official PICO-8 forum](https://www.lexaloffle.com/bbs/?tid=55359). 

Happy learning!

References:

[PICO-8 User Manual, Appendix A: P8SCII Control Codes](https://www.lexaloffle.com/dl/docs/pico-8_manual.html#Appendix_A)

[Learn Hiragana: Tofugu's Ultimate Guide](https://www.tofugu.com/japanese/learn-hiragana/) 

[Learn Katakana: The Ultimate Guide](https://www.tofugu.com/japanese/learn-katakana/)
