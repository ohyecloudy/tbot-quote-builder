# tbot-quote-builder

[tbot-800](https://github.com/ohyecloudy/tbot-800/)이 사용하는 인용구 빌드.

## example

```
$ lein uberjar
$ java -jar target/tbot-quote-builder-standalone.jar -s ./src/q-src.clj -o ./result/quotes -b http://ohrepos.github.io/pquotes-repo/quotes/ -t @book_quote_bot
```

## read more about tbot-800

* [tbot-800 프로젝트 개발 일기](http://ohyecloudy.com/ddiary/categories.html#tbot-800-ref)
* [클로저(clojure)로 짠 트위터 봇 tbot-800을 출동시키고](http://ohyecloudy.com/pnotes/archives/1850)

## license

Copyright © 2013 Oh Jongbin

Distributed under the Eclipse Public License, the same as Clojure.
