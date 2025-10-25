Elijah evelated-potential
==========================

Elijah is:

- ... a high-level language built to entertain it's author's whims.
- ... a historical curiosity.
- ... meant to be easy to use standalone or with existing projects.
- ... free software (LGPL) intended for use on all systems, including Plan9, Haiku and Wasi.
- ... philosophically opposed to semicolons: need to write a better parser, then

`evelated-potential` is:

- ... implemented in Java 17 (We'll investigate later versions with or without Truffle later; and also Scala and or Clojure)
- ... build with maven, with interest in leiningen
- ... a very small, simple build

Instructions
-------------

[https://github.com/tripleo1/evelated-potential](https://github.com/tripleo1/evelated-potential)

```shell
git clone https://github.com/tripleo1/evelated-potential -b giveup
cd elevated-potential
mvnd clean test
# or 
nix-shell -p maven jdk17_headless --pure --command "maven clean test"
```

Revised Goals
--------------

- Slicing and bulldozing into something presentable


Goals
------

- Fiddle with Github `.workflows`
- Make progress towards results (cf `meson-demo`)
- Make it "fun" to look at (`datalog-ts`, Glamorous Toolkit)
- Stop concentrating on "architecture"...
- ... while simultaneously improving architecture
