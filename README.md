# g()('al')

`g()('al')` is a challenge whereby you need to write in as many languages as
possible code which enables the code `g()('al')` to return the string "goal",
the code `g()()('al')` to return the string "gooal", the code `g()()()('al')`
return the string "goooal", etc.

## Rules
1.   *You are encouraged to break the rules, cleverly.*
2.   When executed, the solution must print "goal" with sufficient o's to
     demonstrate the program's functionality.
11.  The code `g()('al')` must appear in the source.
  1.   `g()('al')` must not be a string literal.
  2.   `'al'` must be a string, or your language's equivalent thereof. You may
       use your language's standard method of creating a string (e.x. C should
       use `"`, ruby may use either `"` or `'`).
7.   `g()('al')` may not print the string. If returning a string cannot be done
     in your language, you should submit rationale as to why this is impossible
     for a solution which prints a string to be accepted.
642. You must be able to insert an arbitrary number of `()` calls without
     modification to your solution. Therefore solutions like
     [this][c-limited-calls] are incorrect.
9.  `g()('al')` must be a valid [rvalue] if applicable in your language.
14. `g('al')` must return `"gal"`.
12.  If you have a solution that is close, but does not meet these rules,
     submit it anyway. A close and interesting solution is better than no
     solution.

### Previous Solutions
The more exciting solutions are original, not applying techniques that have
already been discovered. The following generally applicable techniques have
already been discovered:

 * [Self-modifying code][c-self-modify]

## Languages

|               | Solved                 | Improbable              |
|:-------------:|:----------------------:|:-----------------------:|
| C             | [&bull;][c-soln]       |                         |
| C#            | [&bull;][cs-soln]      |                         |
| C++           | [&bull;][c++-soln]     |                         |
| Clojure       | [&bull;][clojure-soln] |                         |
| Common Lisp   | [&bull;][clisp-soln]   |                         |
| Go            | [&bull;][go-soln]      |                         |
| Groovy        | [&bull;][groovy-soln]  |                         |
| Haskell       | [&bull;][hs-soln]      |                         |
| Java          |                        | [&bull;][java-non-soln] |
| JavaScript    | [&bull;][js-soln]      |                         |
| Julia         | [&bull;][jl-soln]      |                         |
| Lua           | [&bull;][lua-soln]     |                         |
| Objective-J   | [&bull;][obj-j-soln]   |                         |
| OCaml         | [&bull;][ocaml-soln]   |                         |
| Perl          | [&bull;][perl-soln]    |                         |
| PHP           |                        | [&bull;][php-non-soln]  |
| Python        | [&bull;][py-soln]      |                         |
| R             | [&bull;][r-soln]       |                         |
| Ruby          |                        | [&bull;][rb-non-soln]   |
| Scala         | [&bull;][scala-soln]   |                         |
| SH            | [&bull;][sh-soln]      |                         |
| BASH          | [&bull;][bash-soln]    |                         |

Help out, add some more languages!

# Editor's Note
This got A LOT more popular than I expected. At the moment, there are 37 pull
requests that I need to look at. Please be patient as it may take me a few days
to get through them all. I'm prioritizing pull requests for new languages above
ones for existing languages.

It would be super helpful if people wanted to help out by:

1. Running other's submissions and confirming that they work correctly.
2. Checking that the submissions aren't too similar to existing solutions.
3. Checking that they follow all the rules.
4. Calling out particularly clever solutions.

Just leave a comment on the pull request with your findings and I'll see it.
Thanks!

[rvalue]: http://en.wikipedia.org/wiki/Value_(computer_science)#lrvalue

[bash-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/bash
[c++-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/c++
[cs-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/c-sharp
[c-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/c
[clojure-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/clojure
[clisp-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/common-lisp
[go-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/go
[groovy-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/groovy
[hs-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/haskell
[js-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/javascript
[jl-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/julia
[lua-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/lua
[obj-j-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/objective-j
[perl-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/perl
[py-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/python
[r-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/r
[scala-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/scala
[sh-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/sh
[ocaml-soln]: https://github.com/eatnumber1/goal/tree/master/solutions/complete/ocaml

[c-self-modify]: https://github.com/eatnumber1/goal/tree/master/solutions/incomplete/c/tolmasky
[c-limited-calls]: https://github.com/eatnumber1/goal/tree/master/solutions/incomplete/c/crawford

[java-non-soln]: https://github.com/eatnumber1/goal/tree/master/non-solutions/java
[php-non-soln]: https://github.com/eatnumber1/goal/tree/master/non-solutions/php
[rb-non-soln]: https://github.com/eatnumber1/goal/tree/master/non-solutions/ruby
