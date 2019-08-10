Regular lines with enter hit one time after end/
are all on the same line, like this.

For a new paragraph to be started 

there must be two spaces

in between lines.

Underscores and asterisks can be used for **BOLD** and _italics_

A single underscore or asterisk will create an *italic* word,

A double of either will create a __bold__ word.

 A ~~Strike through~~ is created with double tilde, a ~single~ tilde will just show tilde.

# Create a heading with a hash

## H2 will be created with two hash, and so on to six.

To make a http://github.com clickable, wrap them in angle brackets

<http://github.com>

[Create clickable text](http://github.com "A space and string in the parentheses will create title tag") wrap the text in square brackets and the link in parentheses.

You can also create shortcuts with keys at the bottom of the document.  Then double square brackets in the body.  

This will link to [github][1]

this will link to [Twitter][Twit]

images are similar to links, a bang immediately precedes the square brackets. 

## Lists

### Ordered lists can be created with

+ plus sign
- minus or dash
* or an asterisk

### Steps

1. Should be created
   * nested lists/images/links have the same rules as top level equals. Bullet points are defined by css at this level.

    this is a new paragraph nested in the first step.

2. with just the number
3. one as the parser
4. will figure out the numbers for you.

### Code Blocks

Indent lines to create a code block:

    let x = 1000;
    const dog = 'Bosco';

Wrap the text with three back ticks, and name the language after the first set to create language specific blocks

```js
$age = 37;
$name = "eric";
echo strtoupper($name);
```

### Tables

This wont work everywhere, add pipes around everything you ant to be a table

|Dogs Name| Dogs Age|
|:--------|:--------|:--------|
|Bosco|6|
|Olive|5|
|Tippy|13|


[1]: http://github.com
[Twit]: http://twitter.com