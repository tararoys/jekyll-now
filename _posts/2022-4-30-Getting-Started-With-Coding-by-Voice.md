---
layout: post
title: Getting Started With Coding by Voice
---

Ever wonder what code dictation looks like? Here I present five levels of code dictation proficiency, from a very beginner level of spelling out the code letter by letter and symbol by symbol all the way up to intermediate level dictation using code structures and language-specific code syntax.

For my demos, I will write out the following code: 


    tag: user.chapters
    -
    chapter next: user.chapter_next()
    chapter last: user.chapter_previous()
    go chapter <number>: user.chapter_jump(number)
    go chapter final: user.chapter_final()

# Tara's Talon Code Dictation Level 0: Spelling Out Code Character by Character

<iframe width="560" height="315" src="https://www.youtube.com/embed/ah7uw-f_MKE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

It's possible to get started dictating code quickly and fairly simply by spelling out the code letter by letter.  In order to do this, you need to know the letter commands and the symbol commands, and more specifically, where to look them up.

I wrote this code using exclusively the commands found on the `alphabet` command list, the `special keys` list, and the `symbols` list. You can bring up these lists by saying `help alphabet`, `help special keys`, and `help symbols.` 

The advantage of these commands is that this is a simple, introductory way to get started.  It also teaches you how to write any word that uses English letters, numbers, and symbols, regardless of how the word spelled. 

The disadvantage is that spelling things out is mentally exhausing even if you know the Talon Phonetic alphabet, and doing this method as your main way of dictating code often leads to vocal strain, which is a demoralizing new injury for many people who use Talon because their hands don't work. 

<table>
<thead><tr><th colspan="2" id="user-letter-list">user.letter list</th></tr></thead><tbody>
<tr>
<td>description : The spoken phonetic alphabet</td>
</tr>
<tr>
<td>air</td>
<td>a</td>
</tr>
<tr>
<td>bat</td>
<td>b</td>
</tr>
<tr>
<td>cap</td>
<td>c</td>
</tr>
<tr>
<td>drum</td>
<td>d</td>
</tr>
<tr>
<td>each</td>
<td>e</td>
</tr>
<tr>
<td>fine</td>
<td>f</td>
</tr>
<tr>
<td>gust</td>
<td>g</td>
</tr>
<tr>
<td>harp</td>
<td>h</td>
</tr>
<tr>
<td>sit</td>
<td>i</td>
</tr>
<tr>
<td>jury</td>
<td>j</td>
</tr>
<tr>
<td>crunch</td>
<td>k</td>
</tr>
<tr>
<td>look</td>
<td>l</td>
</tr>
<tr>
<td>made</td>
<td>m</td>
</tr>
<tr>
<td>near</td>
<td>n</td>
</tr>
<tr>
<td>odd</td>
<td>o</td>
</tr>
<tr>
<td>pit</td>
<td>p</td>
</tr>
<tr>
<td>quench</td>
<td>q</td>
</tr>
<tr>
<td>red</td>
<td>r</td>
</tr>
<tr>
<td>sun</td>
<td>s</td>
</tr>
<tr>
<td>trap</td>
<td>t</td>
</tr>
<tr>
<td>urge</td>
<td>u</td>
</tr>
<tr>
<td>vest</td>
<td>v</td>
</tr>
<tr>
<td>whale</td>
<td>w</td>
</tr>
<tr>
<td>plex</td>
<td>x</td>
</tr>
<tr>
<td>yank</td>
<td>y</td>
</tr>
<tr>
<td>zip</td>
<td>z</td>
</tr>
</tbody></table>

<table>
<thead><tr><th colspan="2" id="user-special-key-list">user.special-key list</th></tr></thead><tbody>
<tr>
<td>description : All special keys</td>
</tr>
<tr>
<td>end</td>
<td>end</td>
</tr>
<tr>
<td>enter</td>
<td>enter</td>
</tr>
<tr>
<td>escape</td>
<td>escape</td>
</tr>
<tr>
<td>home</td>
<td>home</td>
</tr>
<tr>
<td>insert</td>
<td>insert</td>
</tr>
<tr>
<td>pagedown</td>
<td>pagedown</td>
</tr>
<tr>
<td>pageup</td>
<td>pageup</td>
</tr>
<tr>
<td>space</td>
<td>space</td>
</tr>
<tr>
<td>tab</td>
<td>tab</td>
</tr>
<tr>
<td>delete</td>
<td>backspace</td>
</tr>
<tr>
<td>forward delete</td>
<td>delete</td>
</tr>
<tr>
<td>page up</td>
<td>pageup</td>
</tr>
<tr>
<td>page down</td>
<td>pagedown</td>
</tr>
<tr>
<td>menu key</td>
<td>menu</td>
</tr>
<tr>
<td>print screen</td>
<td>printscr</td>
</tr>
</tbody></table>

<table>
<thead><tr><th colspan="2" id="user-symbol-key-list">user.symbol-key list</th></tr></thead><tbody>
<tr>
<td>description : All symbols from the keyboard</td>
</tr>
<tr>
<td>dot</td>
<td>.</td>
</tr>
<tr>
<td>point</td>
<td>.</td>
</tr>
<tr>
<td>quote</td>
<td>'</td>
</tr>
<tr>
<td>apostrophe</td>
<td>'</td>
</tr>
<tr>
<td>L square</td>
<td>[</td>
</tr>
<tr>
<td>left square</td>
<td>[</td>
</tr>
<tr>
<td>square</td>
<td>[</td>
</tr>
<tr>
<td>R square</td>
<td>]</td>
</tr>
<tr>
<td>right square</td>
<td>]</td>
</tr>
<tr>
<td>slash</td>
<td>/</td>
</tr>
<tr>
<td>backslash</td>
<td>\</td>
</tr>
<tr>
<td>minus</td>
<td>-</td>
</tr>
<tr>
<td>dash</td>
<td>-</td>
</tr>
<tr>
<td>equals</td>
<td>=</td>
</tr>
<tr>
<td>plus</td>
<td>+</td>
</tr>
<tr>
<td>tilde</td>
<td>~</td>
</tr>
<tr>
<td>bang</td>
<td>!</td>
</tr>
<tr>
<td>down score</td>
<td>-</td>
</tr>
<tr>
<td>under score</td>
<td>-</td>
</tr>
<tr>
<td>paren</td>
<td>(</td>
</tr>
<tr>
<td>L paren</td>
<td>(</td>
</tr>
<tr>
<td>left paren</td>
<td>(</td>
</tr>
<tr>
<td>R paren</td>
<td>)</td>
</tr>
<tr>
<td>right paren</td>
<td>)</td>
</tr>
<tr>
<td>brace</td>
<td>{</td>
</tr>
<tr>
<td>left brace</td>
<td>{</td>
</tr>
<tr>
<td>R brace</td>
<td>}</td>
</tr>
<tr>
<td>right brace</td>
<td>}</td>
</tr>
<tr>
<td>angle</td>
<td>&lt;</td>
</tr>
<tr>
<td>left angle</td>
<td>&lt;</td>
</tr>
<tr>
<td>less than</td>
<td>&lt;</td>
</tr>
<tr>
<td>rangle</td>
<td>&gt;</td>
</tr>
<tr>
<td>R angle</td>
<td>&gt;</td>
</tr>
<tr>
<td>right angle</td>
<td>&gt;</td>
</tr>
<tr>
<td>greater than</td>
<td>&gt;</td>
</tr>
<tr>
<td>star</td>
<td>*</td>
</tr>
<tr>
<td>hash</td>
<td>#</td>
</tr>
<tr>
<td>percent</td>
<td>%</td>
</tr>
<tr>
<td>caret</td>
<td>^</td>
</tr>
<tr>
<td>amper</td>
<td>&amp;</td>
</tr>
<tr>
<td>pipe</td>
<td> | </td>
</tr>
<tr>
<td>dubquote</td>
<td>"</td>
</tr>
<tr>
<td>double quote</td>
<td>"</td>
</tr>
<tr>
<td>dollar</td>
<td>$</td>
</tr>
<tr>
<td>pound</td>
<td>£</td>
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

# Tara's Talon Coding Level 1: Writing With Words and Phrases

<iframe width="560" height="315" src="https://www.youtube.com/embed/5gDBOBMdShs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Dictating word by word and phrase by phrase levels up my code dictating skills.  When combined with the symbol and special key commands, it is possible to write out code word by word and phrase by phrase.

The advantage of these commands is that this is a simple, introductory way to get started.  It also teaches you how to write any english phrase. 

This method is less mentally taxing than spelling things out letter by letter. 


<table>
<thead><tr><th colspan="2" id="Formatters">Formatters</th></tr></thead><tbody>
<tr>
<td>phrase   &lt;user.text&gt;  </td>
<td>Inserts a phrase</td>
</tr>
<tr>
<td>word  &lt;user.word&gt;  </td>
<td>Inserts a single word.</td>
</tr>
</tbody></table>

# Tara's Talon Code Dictation Level 2: Writing Code With Formatters 

<iframe width="560" height="315" src="https://www.youtube.com/embed/wWWp5jYuYj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Code often has special formats, like putting\_underscores\_in\_phrases (a style called 'snake case' or makingPhrasesBeSmashedTogetherLikeThis (a style called camel case).  This movie shows what's possible when you add formatters to the set of commands used to dictate code.  The formatters are available from the menu `help formatters.`

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
<td>The Quick Brown fox</td>
</tr>
</tbody></table>

# Tara's Talon Code Dictation Level 3: Chaining Formatters With the Over Command

<iframe width="560" height="315" src="https://www.youtube.com/embed/l5-LlS42eGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This video introduces the idea of command chains.  One of the most exciting things about command chains is that you can say several commands, one after the other, and Talon will recognize and do them one after the other.  

With commands like formatters that allows you to say arbitrary phrases, you need to have a word that tells when the phrase is over.  In knausj, that word is the actual word 'over.' 

# Tara's Talon Code Dictation Level 4: Syntax Level Programming With Language Specific Commands

<iframe width="560" height="315" src="https://www.youtube.com/embed/W_xzjVqrAWU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This video is where I start to show off the true power of Talon when dictating code.  Since Talon allows you to define anything as a voice command, that means you can take abstract code syntax like includes and functions and make them into a voice command.  This means, instead of spelling things out character by charact or word by word, you get to think of things at a code syntax level. 

I found this mentally taxing since I have to know what talon syntax is and what the commands are.  Fortunately, I could look up the commands in the Talon context menu with the command `help talon context.`


<table>
<thead><tr><th colspan="2" id="Talon">Talon</th></tr></thead><tbody>
<tr>
<td>description : Talon Syntax File</td>
</tr>
<tr>
<td>dot talon</td>
<td>Insert ".talon". </td>
</tr>
<tr>
<td>setting block</td>
<td>Insert "settings():\n	". </td>
</tr>
<tr>
<td>setting   {user.talon-settings}  </td>
<td> Inserts a particular setting (if it is on the talon settings list</td>
</tr>
<tr>
<td>win require</td>
<td>Insert "os: windows\n". </td>
</tr>
<tr>
<td>mac require</td>
<td>Insert "os: mac\n". </td>
</tr>
<tr>
<td>linux require</td>
<td>Insert "os: linux\n". </td>
</tr>
<tr>
<td>title require</td>
<td>Insert "win.title: ". </td>
</tr>
<tr>
<td>application [require]  {user.talon-apps}  </td>
<td>Inserts the app matcher, if the app named is on the talon-apps list</td>
</tr>
<tr>
<td>mode require   {user.talon-modes}  </td>
<td>Inserts a named talon mode from the talon modes list </td>
</tr>
<tr>
<td>tag require   {user.talon-tags} </td>
<td>Inserts a talon tag from the talon tags list </td>
</tr>
<tr>
<td>tag set {user.talon-tags} </td>
<td> inserts a named tag from the tag list, or if it doesn't recognize the tag name, will insert tag(): </td>
</tr>
<tr>
<td>list  {user.talon-lists} </td>
<td>Inserts the named talon list. </td>
</tr>
<tr>
<td>capture   {user.talon-captures} </td>
<td>Inserts the named talon capture. </td>
</tr>
<tr>
<td>key &lt;user.keys&gt;   over</td>
<td>Inserts a sequence of named keys </td>
</tr>
<tr>
<td>key   &lt;user.modifiers&gt;   over</td>
<td>Inserts the named modifier keyes </td>
</tr>
<tr>
<td>funk  {user.talon-actions}  </td>
<td>Inserts the named action. </td>
</tr>
</tbody></table>