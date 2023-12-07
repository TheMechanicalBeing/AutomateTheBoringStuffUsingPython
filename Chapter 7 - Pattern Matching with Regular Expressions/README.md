# Chapter 7 - Pattern Matching with Regular Expressions

## Exercise 1 - Phone Number and Email Address Extractor

Say you have the boring task of finding every phone number and email address in a long web page or document. If you manually scroll through the page, you might end up searching for a long time. But if you had a program that could search the text in your clipboard for phone numbers and email addresses, you could simply press CTRL-A to select all the text, press CTRL-C to copy it to the clipboard, and then run your program. It could replace the text on the clipboard with just the phone numbers and email addresses it finds.

### Requirements
- Use the `pyperclip` module to copy and paste strings
- Create two regexes, one for matching phone numbers and the other for matching email addresses
- Find all matches of both regexes
- Format the matched strings into a single string to paste
- Display some kind of message if no matches found in the text