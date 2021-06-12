# Down to the Metal

_How does the text we type turn into the computer actually doing things?_

As programmers, we express ourselves in code. Our code's structure and meaning
allows us to describe what we want our programs to do, but the process by which
our code becomes actual behaviour can be rather opaque. That's especially true
for those of us working JavaScript, where we can often write code in language 
which gets translated into JavaScript, only for it to be transformed into 
another version of JavaScript, which is in turn becomes behaviour on some other
computer in some other runtime environment.

Starting with a small toy language, we'll look at the steps that take us from a
text file to actual computer behaviour. We'll look at the various steps that
take us from code to executing code in an interpreter. We'll follow that up with
examining how we might enhance the toolchain with optimisations, obfuscation,
and linting, finishing up by moving from interpretation to compilation.

---

Jez Higgins is a freelance software grandad. He mucks in with programming, 
lends a hand with build & deployment processes, provides a leg up with TDD
practices, and keeps an eye on the young 'uns so they don’t get trapped down 
the old mine shaft.

