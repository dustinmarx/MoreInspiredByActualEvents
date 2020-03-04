The Java programming language provides numerous situations in which the developer has the choice to
_explicitly specify_ something or to allow that same thing to be _implicitly assumed_. Examples of these
are listed here.

Java Construct | Explicit Versus Implicit
-------------- | ------------------------
No-arguments Constructor | A no-arguments constructor is implicit for a class that does not explicitly define any constructors.
Interface is Abstract | A Java `interface` is implicitly `abstract` ([source](https://docs.oracle.com/javase/tutorial/reflect/class/classModifiers.html))
Interface Method Modifiers | An interface method is implicitly `public` ([source](https://docs.oracle.com/javase/tutorial/java/IandI/interfaceDef.html))
Class is Package-Private | Unless a "top level" access level modifier (`public`, `private`, or `protected`) is specified, a class is implicitly _package-private_ (no explicit modifier) ([source](https://docs.oracle.com/javase/tutorial/java/javaOO/accesscontrol.html)) 
Class Field/Method Modifier | Unless a "top level" access level modifier (`public`, `private`, or `protected`) is specified, a class member is implicitly _package-private_ (no explicit modifier) ([source](https://docs.oracle.com/javase/tutorial/java/javaOO/accesscontrol.html))
`.toString()` Invocations | In some cases, the `.toString()` method is called implicitly on Java objects.
Inherited / Implemented Method Javadoc Comments | Although `{@inheritDoc}` can be used to explicitly inherit method-level Javadoc comments from a parent class or implemented interface, this [is unnecessary](http://marxsoftware.blogspot.com/2016/11/inheriting-javadoc-method-comments.html) unless it is desirable to add to the comments.
