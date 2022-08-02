
***

![/Crystal_language_logo.svg](/Crystal_language_logo.svg)

### Learning Crystal (programming language)

I know very little about the Crystal programming language. This document will go over all of my knowledge of the Crystal programming language.

#### Hello World in Crystal

This is how you make a normal Hello World program in Crystal:

```crystal
puts "Hello World"
```

It is identical to Ruby.

#### Object Oriented hello world in Crystal

This is how you make an OOP (Object Oriented Programming) hello world program in Crystal:

```crystal
class Greeter
  def initialize(@name : String)
  end

  def salute
    puts "Hello #{@name}!"
  end
end

g = Greeter.new("world")
g.salute
```

#### Comments in Crystal

Comments in Crystal are the same as in languages like Ruby.

##### Single line comments

Single line comments in Crystal are written like so:

```crystal
# This is a single line comment
```

##### Multi-line comments

I don't know if Crystal supports multi-line comments.

#### Break keyword in Crystal

Crystal supports the `break` keyword.

```crystal
break
```

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

##### Shebang in Crystal

Crystal is a language that uses a shebang. It is written like so:

```crystal
#!/usr/bin/env crystal
puts "Crystal program"
```

_/!\ This example has not been tested yet, and may not work_

#### Other knowledge of the Crystal programming language

1. Crystal is a language by Ary Borenszweig, Juan Wajnerman, and Brian Cardiff

2. Crystal is not a semicolon and curly bracket language

3. Crystal uses the `*.cr` file extension by default. I don't know if it uses any other file extensions.

4. Crystal is designed to have the "elegance and productivity" of Ruby, and the "speed, efficiency, and type safety" of C (or another compiled language)

5. Crystal is based on Ruby in design, and C in structure

6. Crystal was created in 2014

7. Crystal is not one of the top 50 programming languages (as of 2022, July 31st, it has never ranked 50 or higher on the TIOBE index, but it has ranked in the top 100) source: [TIOBE index](https://www.tiobe.com/tiobe-index/)

8. Crystal is a language recognized by GitHub (as of 2022, Tuesday, August 2nd)

9. No other knowledge of the Crystal programming language

#### Additional comments

1. I have not yet memorized the names of the developers

2. No other additional comments available

***

## File info

**File type:** `Markdown document (*.md *.mkd *.mdown *.markdown)`

**File version:** `1 (2022, Tuesday, August 2nd at 3:43 pm PST)`

**Line count (including blank lines and compiler line):** `156`

***

## File history

<details><summary><p>Click/tap here to expand/collapse the history for this file</p></summary>

<details><summary><p><b>Version 1 (2022, Tuesday, August 2nd at 3:43 pm PST)</b></p></summary>

> Changes:

> * Started the file

> * Added the `title` section

> * Added the `Hello World in Crystal` section

> * Added the `Object Oriented Hello World in Crystal` section

> * Added the `Comments in Crystal` section

> > * Added the `Single line comments` subsection

> > * Added the `Multi-line comments` subsection

> * Added the `break keyword in Crystal` section

> * Added the `Shebang in Crystal` section

> * Added the `other knowledge of the Crystal programming language` section

> * Added the `Additional comments` section

> * Added the `file info` section

> * Added the `file history` section

> * No other changes in version 1

</details>

</details>

***
