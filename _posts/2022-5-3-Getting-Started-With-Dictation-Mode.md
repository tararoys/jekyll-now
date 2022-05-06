---
layout: post
title: Getting Started With Dictation Mode
---

Welcome to Dictation Mode training!  Soon you will be a great dictator! 

This tutorial is all about how to dictate words.  This does not include editing commands.  Editing is a separate tutorial.

Before doing any sort of voice work, it is very important to warm up.  Short warm ups are incredibly important in caring for and maintaining your body.  As farmers say, "If You Don't Schedule Time For Maintenance, Your Equipment Will Schedule It For You." Now is an excellent time to take five minutes, take care of your vocal equipment, and hum the 'Star Spangled Banner' through a straw along with Ingo Titze. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/0xYDvwvmBIM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

All warmed up?  Excellent!  

# Dictation Mode 


To get into dictation mode, say `dictation mode.`  This turns off all of the commands except the [dictation commands.](https://tararoys.github.io/cheatsheet#Dictation-Mode)

By default, dictation mode has several autoformatting and capitalization features.  When in dictation mode, it keeps track of when you have said a sentence-terminating character like a period, an exclamation point, or a question mark.  When it hears those characters, it will automatically space and capitalize the next phrase. It will also properly space things like commas, semicolons, and so on.  

For example, go to dictation mode and say: 

    When the cow jumped over the moon comma the cat was playing the fiddle period

The above does not have to be a full command.  You can say it word by word, or in phrases, or all at once.  The result will be, 'When the cow jumped over the moon, the cat was playing with the fiddle.'


<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>

# Undoing Things

The command `scratch that` is often used to correct dictation.  `Scratch that` has a couple of caveats.  

The way `scratch that` works is that it counts the number of keystrokes Talon typed during the last phrase, and deletes that number of keystrokes.  

As a result, if you move the cursor at all, it will start deleting from wherever you put the cursor.  This also means that if you are using a program with certain forms of auto-complete it will throw off Talon's count and `scratch that` won't delete the last phrase you typed.  

If `scratch that` messes up, the best way to fix it is to switch to command mode with the command `command mode` and start saying `undo that.` 

The `undo that` command uses the undo function of whatever program you are in.  However, that also has some issues.  For example, when you have said a long phrase, the program you are typing into will often interpret each word Talon types as a separate phrase.  So even though you said 'the quick brown fox jumped over the lazy dog' really quickly, you have to say `undo that` 9 times to delete the phrase word by word.  This is why `scratch that` is the preferable command, even if it does not do what you expect when you move the cursor.  (You can also say `undo that nine times` to repeat the undo command nine times, but who has time to do math while typing?)

If you want to see `scratch that` in action, switch to command mode and say `recent list.` This opens the 'recent phrases' list, which keeps track of the last forty things you've said.  Say `scratch that` and watch the first phrase disappear off the list.  

![recent phrases](/assets/2022_05_04T17_51_23__Notepad.png)


#  Adding Custom Vocabulary 
    
What if you want to add special words, like a name, or a technical term, to the dictation mode? If you add the word to **knausj_talon/settings/additional_words.csv**, Talon will start dictating it when you pronounce it.  If Talon doesn't start dictating it, add a pronunciation hint.  For example, I can add the following line to additional_words.csv. 

    knausj, nous ja

As you can see, I added the word knausj with a pronunciation hint 'nous ja.'  Now, when I say 'nous ja' it types out knausj, the name of the default Talon repository.  Add a word like knausj or your name to additional words.

 

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>


# Adding Punctuation

Dictation mode will substitute words with the right punctuation, appropriately spaced, for the following punctuation symbols from the [punctuation list](https://tararoys.github.io/cheatsheet#user-punctuation-list):


<table>
<thead><tr><th colspan="2" id="user-punctuation-list">user.punctuation list</th></tr></thead><tbody>
<tr>
<td>description : words for inserting punctuation into text</td>
</tr>
<tr>
<td>`</td>
<td>`</td>
</tr>
<tr>
<td>,</td>
<td>,</td>
</tr>
<tr>
<td>back tick</td>
<td>`</td>
</tr>
<tr>
<td>grave</td>
<td>`</td>
</tr>
<tr>
<td>comma</td>
<td>,</td>
</tr>
<tr>
<td>period</td>
<td>.</td>
</tr>
<tr>
<td>full stop</td>
<td>.</td>
</tr>
<tr>
<td>semicolon</td>
<td>;</td>
</tr>
<tr>
<td>colon</td>
<td>:</td>
</tr>
<tr>
<td>forward slash</td>
<td>/</td>
</tr>
<tr>
<td>question mark</td>
<td>?</td>
</tr>
<tr>
<td>exclamation mark</td>
<td>!</td>
</tr>
<tr>
<td>exclamation point</td>
<td>!</td>
</tr>
<tr>
<td>asterisk</td>
<td>*</td>
</tr>
<tr>
<td>hash sign</td>
<td>#</td>
</tr>
<tr>
<td>number sign</td>
<td>#</td>
</tr>
<tr>
<td>percent sign</td>
<td>%</td>
</tr>
<tr>
<td>at sign</td>
<td>@</td>
</tr>
<tr>
<td>and sign</td>
<td>&amp;</td>
</tr>
<tr>
<td>ampersand</td>
<td>&amp;</td>
</tr>
<tr>
<td>dollar sign</td>
<td>$</td>
</tr>
<tr>
<td>pound sign</td>
<td>£</td>
</tr>
</tbody></table>
    
# Adding Quotation Marks

Dictation mode handles quotation marks a little oddly, so you have to know the right voice command to get quotation marks to do the appropriate spacing.  Specifically, you have to use the command 'open quote' to start a quotation and 'close quote' to create a quotation with a space after it. 

Say the command 

    open quote I like myself period close quote I said open quote because I am awesome exclamation mark close quote

The result will be "I like myself." I said, "because I am awesome!" 
    
<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>


Note: These commands are all handled by the prose snippit list, and you currently can't look them up with the `help context dictation` help menu.  The only current way to figure out what is on the list commands are without having someone tell you what they are is to check out the [prose snippit list](https://tararoys.github.io/cheatsheet#user-prose-snippit-list) or to know your way around the knausj source code and understand how lists work on a python code level.

These commands are located on the [prose snippit list](https://tararoys.github.io/cheatsheet#user-prose-snippets-list).

<table>
<thead><tr><th colspan="2" id="user-prose-snippets-list">user.prose-snippets list</th></tr></thead><tbody>
<tr>
<td>description : Snippets that can be used within prose</td>
</tr>
<tr>
<td>spacebar</td>
<td> </td>
</tr>
<tr>
<td>new line</td>
<td>
&lt;br /&gt;
</td>
</tr>
<tr>
<td>new paragraph</td>
<td>
&lt;br /&gt;

&lt;br /&gt;
</td>
</tr>
<tr>
<td>open quote</td>
<td>“</td>
</tr>
<tr>
<td>close quote</td>
<td>”</td>
</tr>
<tr>
<td>smiley</td>
<td>:-)</td>
</tr>
<tr>
<td>winky</td>
<td>;-)</td>
</tr>
<tr>
<td>frowny</td>
<td>:-(</td>
</tr>
</tbody></table>

# Adding New Lines

The easy way to add new lines is  the 'new line' command, which inserts a new line, and the 'new paragraph' command, which inserts two new lines to symbolize the beginning of a new paragraph. 

Otherwise, you can insert a new paragraph with the `press newline` key.  

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>


# Writing Numbers

If you want a number written out like 123 instead of one hundred twenty three, prefix it with the word 'numeral.'  

For example, say the command 

    numeral one hundred twenty three

The result is 123.

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>

The command 
    
    numeral one two three

will also result in 123.

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>

The command 

    numeral one hundred dot five six

will result in 100.56

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>


Or the command 

    numeral eight colon fifty six.  

will result in 8:56

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>

(Note: These commands are all handled by the prose number capture and you can't look them up with the `help context dictation` help menu.  The only current way to figure out what the `numeral` commands are without having someone tell you what they are is to check out the [prose number capture on my cheatsheet](https://tararoys.github.io/cheatsheet#user-prose-number-capture) or to know your way around the knausj source code and understand how talon captures work on a code level.)

# Spelling Words

It is possible to spell out words with the `spell that` command.  

For example, say the command:

    spell that air pit pit look each

This spells the word `apple.`

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>

People often want to spell proper names.  It is possible to capitalize the thing you are formatting by putting the 'title' formatter after the the 'spell that' command.

    spell that title trap air red air

This spells my name, Tara. 

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>

# Formatting text 

Many times people want to capitalize text, such as book titles, article titles or other things.  To format a phrase, you can say a the word `formatter` followed by the type of formatting you want, followed by the phrase you want to format.  For example to format a phrase like a book title, say, 

    formatted title books are awesome

This results in `Books Are Awesome.` 

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>

The following is a list of formatters currently available in knausj-talon. 

<table>
<thead><tr><th colspan="2" id="user-formatters-list">user.formatters list</th></tr></thead><tbody>
<tr>
<td>description : list of formatters</td>
</tr>
<tr>
<td>allcaps</td>
<td>THE QUICK BROWN FOX</td>
</tr>
<tr>
<td>alldown</td>
<td>the quick brown fox</td>
</tr>
<tr>
<td>camel</td>
<td>theQuickBrownFox</td>
</tr>
<tr>
<td>dotted</td>
<td>the.quick.brown.fox</td>
</tr>
<tr>
<td>dubstring</td>
<td>"the quick brown fox""</td>
</tr>
<tr>
<td>dunder</td>
<td>__the__quickbrownfox__</td>
</tr>
<tr>
<td>hammer</td>
<td>TheQuickBrownFox</td>
</tr>
<tr>
<td>kebab</td>
<td>the-quick-brown-box</td>
</tr>
<tr>
<td>packed</td>
<td>the::quick::brown::fox</td>
</tr>
<tr>
<td>padded</td>
<td> the quick brown fox </td>
</tr>
<tr>
<td>slasher</td>
<td>/the/quick/brown/fox</td>
</tr>
<tr>
<td>smash</td>
<td>thequickbrownfox</td>
</tr>
<tr>
<td>snake</td>
<td>the_quick_brown_fox</td>
</tr>
<tr>
<td>string</td>
<td>'the quick brown fox''</td>
</tr>
<tr>
<td>title</td>
<td>The Quick Brown Box</td>
</tr>
</tbody></table>

# Selecting The Last Phrase

The command `select that` selects the last phrase spoken.  This is very useful if you want to reformat the thing you just said- such as capitalizing the last phrase to turn it into a book title.  

When paired with the `format selection <user.formatters>` command, it becomes a powerful way to quickly properly format what you just said.  

Say a phrase into the text box below, say `select that`, then say `format selection title` to format what you said into a book title. 

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true> </span></div>

# To Press a Sequence of Keys on the Keyboard 
Oftentimes there are keys you want to press on a keyboard, such as symbols that are not recognized by dictation mode.  To press a sequence of keys on the keyboard, use the press command.  For example:

    press shift trap air look odd near ampersand

This spells out 'Talon&'.

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>

You can also press keyboard shortcuts such as the 'file save' keyboard shortcut `ctrl-s` on Windows or `command-s` on Mac: 

    press control sun
    press command sun

# Capitalizing A Single Word

Often, the auto-capitalization does not work, becuase you haven't said a period or other sentence-ending character to terminate the last sentence.  You can capitalize a single word with the command 'cap.' 

    cap apple

results in 'Apple.' 


<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>

Somtimes you say a word, and then immediately decide that you wanted that word capitalizied.  The command `cap that` capitalizes the first word of the last phrase you said.  

This command is especially useful when Talon has lost track of where it is in the document and whether it is supposed to auto-capitalize a word. Whether the dictation.py file thinks a word should be auto-capitalized depends entirely on the last commands you said- so if you say a command, then move the cursor to a different place in the document, the dictation.py command will have no idea that you moved elsewhere in the document and will still be capitalizing (or not capitalizing) things based on the things you said, not where you actually are.  The `cap that` command is there to quickly fix auto-capitalization issues caused by moving around like that. 

# Writing Out A Word That Is Also A Talon Command

Sometimes you actually want to write out the word 'period' instead of the symbol '.'.  The escape command is for when you want to write out a word that would otherwise be a command. 

    escape period

Results in spelling out the word period.  

<div>Practice Here: <span style = "border: solid black 2px; min-width: 100px; display: inline-block " class= "textarea" contenteditable = true>   </span></div>
