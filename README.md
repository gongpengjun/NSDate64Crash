NSDate64Crash
=============

a little project to demonstrate NSDate crashed on iOS 64bit devices

NSDate object is often implemented as Tagged Pointer (NSTaggedDate) on 64 bit architecture, if we add associated objects on it, it will crash your app.

Reference:

 - Mike Ash《Let's Build Tagged Pointers》http://goo.gl/c7DGNq
 - Hamster Emporium《Non-pointer isa》http://goo.gl/dATsy7
