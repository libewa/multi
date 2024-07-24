# multi
```
          0 0   0
0000  0 0 0 00   
0 0 0 0 0 0 0   0
0 0 0  00 0 00  0
```
A snake game that evolved from an attempt at creating a multiplayer game on the TI82STATS programmable graphing calculator.

## Why does this exist?

The TI82STATS was my school-provided graphing calculator, and, as it is any student's instinct, we started to create games using the prototype version of TI-BASIC on that calculator (it wasn't even called that until the 83+)

This is my attempt at creating a multiplayer game where two players can move around. It does not work, but I reused part of the codebase to create a simple Snake game, and that one does everything it's supposed to do (which isn't much).

![It ain't much, but it's honest work.](https://i.kym-cdn.com/entries/icons/original/000/028/021/work.jpg)

## What do the programs do?

[`COBRA.8xp`](./COBRA.8xp) The snake game.

[`MPLAUNCH.8xp`](./MPLAUNCH.8xp) A launcher that allows you to pick what game to launch. Basically a `Menu()` demo.

[`MULTI1.8xp`](./MULTI1.8xp) The client for player 1 (`X`)

[`MULTI2.8xp`](./MULTI2.8xp) The client for player 2 (`O`)

[`UNI.8xp`](./UNI.8xp) A version with all of the multiplayer code removed. You just move an X in a box.

[`Str7.8xs`](./Str7.8xs) Contains the end screen for all games.

[`multi.8xg`](./multi.8xg) A group to send all programs at once. Basically the graphing calculator version of downloading a zip file.

## How do I install it?

Download [`multi.8xg`](./multi.8xg) and send it to your calculator using TI-Connect, TI-Connect CE or TiLP, depending on your calculator and computer. See https://ticalc.org/basics/linking/software.html for a compatibility guide.

Some people apparently have issues using group files. If you are one of them, try sending each file individually. TI-Connect allows dropping multiple files at once.