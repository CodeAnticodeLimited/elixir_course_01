# Elixir workshop 1

This will be a gentle introduction to Elixir. It assumes no previous experience with the language, however I _will_ assume that you have a reasonable level of experience with at least one other programming language and basic programming concepts.

The first few workshops will focus on gently introducing you to the language through simple excercises inspired largely by [Advent of Code](https://adventofcode.com/). By the end of each workshop, you will have the skills and knowledge to tackle one or more Advent of Code 2017 challenges in Elixir.

## What you will learn

By the end of this workshop you will be familiar with:

- basic Elixir syntax
- the difference between .ex and .exs files
- compiling and running Elixir code
- using `iex` for interactively developing in Elixir
- basic data types in Elixir such as atoms, lists and maps
- how Elixir code is structured using modules and functions
- approaching solutions as a series of data transformations
- how pattern matching works and why it is so powerful
- 'functional' approaches to working with lists

Although not explicitly covered in the workshop, the provided sample code also demonstrates:

- writing tests with ExUnit
- structuring an Elixir project to use with `mix`

## Challenge #1 part 1

The once simple tradition of children sending letters to Santa has come under attack. Ever since LettersToSanta.com launched, there has been a sharp spike in the number of phishing attempts and viagra adverts in Santa's mailbox. There simply aren't enough elves in the North Pole to assign to sorting all the real letters from the junk, so this year Santa has insisted on a CAPTCHA challenge for all online gift requests.

To keep it simple, the challenge format is the same for all children: write only the uppercase letters for the given CAPTCHA.

For example:

- `AAAbbb` produces `AAA`, because only the letters `AAA` are upper-cased
- `AaabB` produces `AB`
- `abcdefghijk` produces an empty string, because no letter is upper-cased

## Challenge #1 part 2

The Finnish government has registered an official complaint with the EU claiming that Santa's CAPTCHA strategy discriminates against the Finnish language by removing letters instead of adding extra ones. To avoid large fines which would shut down Christmas, Santa has agreed to provide a different challenge for requests from Finnish IP addresses.

For Finnish CAPTCHAs, lower-case letters should not be removed but rather replaced by two of their upper-case equivalent.

For example:

- `ABcD` produces `ABCCD`, because the lowercase `c` is replaced with `CC`
- `AAAbbb` produces `AAABBBBBB`, because every `b` is replaced with `BB`
- `AaabB` produces `AAAAAB`
- `abcdefghijk` produces `AABBCCDDEEFFGGHHIIJJKK`

## Advent of Code 2017 Day #1

By the time you have finished these challenges, you should have all that you need to solve your first real Advent of Code challenge.

https://adventofcode.com/2017/day/1
