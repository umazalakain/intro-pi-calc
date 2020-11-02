Title: Mechanising the Linear π-Calculus

The π-calculus is a computational model for communication and concurrency. The
linear π-calculus restricts the π-calculus by demanding that every communication
channel is used exactly once. This results in more fine grained control over
communication, avoids race conditions, and is in itself enough to serve as a
target language to which the session-typed π-calculus can be compiled to.

This talk will focus on mechanizing the linear π-calculus. I will first present
a mechanized syntax and an operational semantics for the untyped π-calculus. On
top of that, I will use leftover typing to define a resource-aware type system
that is parametrized by a set of usage coalgebras. I will compare this type
system with its more traditional alternative, and comment on some of its type
safety properties.

Finally, I will briefly introduce some of our ongoing research, which aims to
mechanize the decidable typechecking of the linear π-calculus. We do so by
borrowing ideas from co-contextual type checking algorithms and applying them to
the linear π-calculus. This results in a constraint satisfaction problem that,
when satisfied, returns type substitutions that can be used to mechanically
build typing derivations for terms.
