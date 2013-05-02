# sugar-chararray

Sugar array methods ON STRINGS!  This simply takes all array methods and makes
them work on the string as if it were an array of characters.  It is
effectively equivalent to calling `chars()`, then the function, then `join("")`
if an array of strings is returned.

```js
"hello".unique()   === "hello".chars().unique().join("")
"hello".count("l") === "hello".chars().count("l")
```

## Usage

Run the file however you wish.  Then simply call array methods on strings.

```js
"aewee5beb5h".sort()
```

Just note that while some array methods change the original the string versions
always return a new string.

Have fun!
