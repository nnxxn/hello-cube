# _Hello_ _Cube_: an absolutely minimal "Hello World"-type 3d app, using Kivy and OpenGL

So, you're reasonably familiar with python, and it just happens so that you want to do something that involves 3d graphics. Preferably something that can run on your phone or tablet. And you've read about this thing called Kivy, and you've read that it allows you to write an app for Android or iOS, using python.
	
And then it turns out that Kivy's graphics is mostly 2d; but on the other hand, Kivy itself relies on OpenGL (which is available on most of today's devices, including mobile ones) and OpenGL certainly _is_ 3d. So, what you wanted to do should be doable. And Kivy even includes an example -- that "rotating monkey head" -- which shows you how to do 3d stuff. But still: in addition to learning Kivy, it looks like you'll need to learn at least the very basics of OpenGL, and its GLSL language.

But even this simple 3d monkey example involves a bunch of stuff you might not know yet, stuff you'll _also_ have to learn before you can fully understand the example's code -- like, how to read a file in the **.obj* Blender format, or some of the laws of light reflection.

Wouldn't it be nice to start with an even _simpler_ example of how to do 3d with Kivy? An example that consists entirely of only about one screenful of code? If so, say hello to ''_Hello_ _Cube_''. All it does is display a rotating wireframe cube, and it's meant to be as simple and as easy to understand as possible. And it's meant to be useable as a starting point for doing something more interesting.
