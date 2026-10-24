---
source:
  - recepgur07-bot.github.io/tr/harfoni/kilavuz.md
  - harfoni/app/Views/HowToPlayView.swift
layout: default
lang: en
title: Harfoni user guide
permalink: /en/harfoni/guide/
alt_url: /tr/harfoni/kilavuz/
description: Harfoni's game modes, scoring, ranks, hints and Touch Area gestures. Harfoni is in Turkish only; button names are given in Turkish.
---
<!-- Source: tr/harfoni/kilavuz.md (from the in-app Nasıl Oynanır screen, HowToPlayView.swift). Harfoni has no English interface, so UI names stay in Turkish. Update both guides together. -->

# Harfoni user guide

Harfoni is available in Turkish only: the interface, the menus and the words you build are all Turkish. The App Store page may list English as a language; that label is incorrect. This guide explains the rules in English and gives every button name exactly as it appears in the app, in Turkish.
{: .lead}

<nav class="toc" aria-labelledby="toc-heading" markdown="1">
<h2 id="toc-heading">On this page</h2>

1. [The basic rule](#rule)
2. [Levels (Bölümler)](#levels)
3. [Points and ranks](#points)
4. [Controls](#controls)
5. [Hints and hint credits](#hints)
6. [Daily Puzzle (Günün Bulmacası)](#daily)
7. [Against the Clock (Zamana Karşı)](#clock)
8. [Anagram](#anagram)
9. [Touch Area (Dokunmatik Alan)](#touch)
10. [Free version and Full Version](#price)
</nav>

<h2 id="rule">1. The basic rule</h2>

You get the letters of a word, shuffled. You build meaningful Turkish words from them. Each letter can be used in a word at most as many times as it is given; you do not have to use every letter.

- **Target word:** a word you must find in the level. The level ends when all are found.
- **Bonus word:** a valid word that is not a target. It gives 1 point.

Common Turkish words and their frequent inflected forms count. Proper names, abbreviations and very rare words do not.

The shortest accepted word depends on the number of letters and is announced at the start of the level and in the status summary. Unless the level says otherwise: with 4 letters, 3–4 letter words; with 5, 3–5; with 6, 4–6; with 7, 5–7; with 8, 6–8.

[Back to top](#icerik){: .top}

<h2 id="levels">2. Levels (Bölümler)</h2>

Levels follow a single path. The <span lang="tr">Devam et</span> (Continue) button on the main screen always takes you to the next level. Finished levels are not replayed before their turn comes again.

If you take a break, the words you found are saved and you continue where you left off. Letters and word length grow as you progress, with easier levels in between.

At the end of a level you can go back and keep looking for the remaining bonus words, or reveal the ones you missed. After revealing, no new words count in that level.

[Back to top](#icerik){: .top}

<h2 id="points">3. Points and ranks</h2>

- Target word: as many points as it has letters (3 for a 3-letter word, 6 for a 6-letter word).
- Bonus word: 1 point.
- Word opened with a hint: 1 point.

Daily Puzzle and Anagram points are added to your total; Against the Clock points are not. As your total grows your rank rises, and each new rank gives 3 hint credits.

<details markdown="1">
<summary>Ranks and the points they need</summary>

- <span lang="tr">Acemi</span>: start
- <span lang="tr">Çırak</span>: 750 points
- <span lang="tr">Kalfa</span>: 2,250 points
- <span lang="tr">Usta</span>: 5,500 points
- <span lang="tr">Bilge</span>: 10,500 points
- <span lang="tr">Üstat</span>: 17,500 points
- <span lang="tr">Laf Cambazı</span>: 26,500 points
- <span lang="tr">Söz Ehli</span>: 37,500 points
- <span lang="tr">Hezarfen</span>: 50,000 points
- <span lang="tr">Allame</span>: 65,000 points

After <span lang="tr">Allame</span>, every 20,000 points adds <span lang="tr">Allame 2</span>, <span lang="tr">Allame 3</span> and so on. The statistics screen tells your rank and the points left to the next one.
</details>

[Back to top](#icerik){: .top}

<h2 id="controls">4. Controls</h2>

Tap letters to build your word; the selected letters are added to the field at the top.

- Tapping a letter selects it; tapping a selected letter again undoes it.
- <span lang="tr">Sil</span> (Delete) removes the last selected letter.
- <span lang="tr">Sıfırla</span> (Reset) clears the whole selection.
- <span lang="tr">Karıştır</span> (Shuffle) changes the order of the letters.

You can also type: write in the text field at the bottom and press send. With VoiceOver the screen reads top to bottom: status first, then the letters, then the text field and buttons.

[Back to top](#icerik){: .top}

<h2 id="hints">5. Hints and hint credits</h2>

When you are stuck, you can pick one of three hints. The cost is the same in every mode:

- <span lang="tr">Anlamdan Bul</span> (2 credits): shows a short meaning of the word.
- <span lang="tr">İlk Harf ve Uzunluk</span> (3 credits): shows the first letter and the length.
- <span lang="tr">Kelimeyi Göster</span> (5 credits): reveals the word.

The remaining-words list and Shuffle are free. You start with 10 hint credits. Hint credits cannot be bought; you earn them only by playing:

- Finishing a level without a hint: +1
- Finding all targets and bonus words in a level: +1
- Solving the Daily Puzzle: +1; finding everything including bonuses: +3 in total
- Every 5 anagrams: +1
- A new rank: +3
- In Against the Clock, each of 30, 60, 100, 125 and 150 points in one round: +1

If you reveal the remaining words, the find-everything reward is not given.

[Back to top](#icerik){: .top}

<h2 id="daily">6. Daily Puzzle (Günün Bulmacası)</h2>

Everyone gets the same puzzle each day, with 6 or 7 letters. The rules are the same as in levels. After solving it you can reopen it during the day and keep looking for bonus words. A new puzzle opens when the day changes; a missed day does not come back. You can share your result after solving.

[Back to top](#icerik){: .top}

<h2 id="clock">7. Against the Clock (Zamana Karşı)</h2>

You get a 7-letter source word. In 90 seconds you find as many words of at least 3 letters as you can. Hints are not used in this mode.

- 3 letters: 4 points
- 4 letters: 7 points
- 5 letters: 11 points
- 6 letters: 16 points
- 7 or more letters: 22 points

When time runs out with at least 30 points, you are offered 15 extra seconds for 3 hint credits.

[Back to top](#icerik){: .top}

<h2 id="anagram">8. Anagram</h2>

The letters are shuffled. Use every letter once to find the meaningful word; shorter words do not count. Some letter sets make more than one word; then the top of the screen says how many, and the round ends when all are found. Points and hint costs are the same as in the main game.

[Back to top](#icerik){: .top}

<h2 id="touch">9. Touch Area (Dokunmatik Alan)</h2>

Double-tap the <span lang="tr">Dokunmatik alan</span> button on the game screen to turn the whole screen into one touch area. A two-finger double tap also turns it on and off. If <span lang="tr">"Oyunlara dokunmatik modla başla"</span> is on in Settings, games start in this area. Every command is also in the VoiceOver actions list.

<details markdown="1">
<summary>Touch Area gestures</summary>

Letters:

- One-finger flick right: next letter
- One-finger flick left: previous letter (wraps around)
- Single tap: reads the current letter
- Double tap: selects the letter
- One-finger touch and hold: reads all letters

Typed word:

- Two fingers left: deletes the last letter
- Two fingers right: sends the word
- Two fingers down: reads what you typed

Information:

- Three fingers up: status (time or level, points, found, remaining, bonus, hint credits, rank)
- Three fingers down: found words
- Three fingers right: hint
- Three fingers left: number of letters and the letters

Exit and keyboard:

- Two fingers up: leaves the area and moves to the text field; the keyboard opens
- Two-finger double tap or two-finger touch and hold: leaves the area
</details>

To type in Braille, use the iPhone's Braille Screen Input. First swipe up with two fingers to move to the text field, then turn on Braille Screen Input. In Braille, a line break sends the word.

[Back to top](#icerik){: .top}

<h2 id="price">10. Free version and Full Version</h2>

- The first 25 levels and the first 25 anagrams are free.
- The Daily Puzzle is free every day.
- Against the Clock has 3 free rounds a day, renewed daily.

The one-time Full Version unlocks every level, every anagram and unlimited Against the Clock rounds. There is no subscription and there are no ads.

[Back to top](#icerik){: .top}
