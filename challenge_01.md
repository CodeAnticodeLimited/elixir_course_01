# Challenge #1

## Part 1

The once simple tradition of children sending letters to Santa has come under attack. Ever since LettersToSanta.com launched, there has been a sharp spike in the number of phishing attempts and viagra adverts in Santa's mailbox. There simply aren't enough elves in the North Pole to assign to sorting all the real letters from the junk, so this year Santa has insisted on a CAPTCHA challenge for all online gift requests.

To keep it simple, the challenge format is the same for all children: write only the uppercase letters for the given CAPTCHA.

For example:

- `AAAbbb` produces `AAA`, because only the letters `AAA` are upper-cased
- `AaabB` produces `AB`
- `abcdefghijk` produces an empty string, because no letter is upper-cased

## Part 2

The Finnish government has registered an official complaint with the EU claiming that Santa's CAPTCHA strategy discriminates against the Finnish language by removing letters instead of adding extra ones. To avoid large fines which would shut down Christmas, Santa has agreed to provide a different challenge for requests from Finnish IP addresses.

For Finnish CAPTCHAs, lower-case letters should not be removed but rather replaced by two of their upper-case equivalent.

For example:

- `ABcD` produces `ABCCD`, because the lowercase `c` is replaced with `CC`
- `AAAbbb` produces `AAABBBBBB`, because every `b` is replaced with `BB`
- `AaabB` produces `AAAAAB`
- `abcdefghijk` produces `AABBCCDDEEFFGGHHIIJJKK`
