Tic Tac Toe
------------
pygame is a free and open-source cross-platform library for the development of multimedia applications like video games using Python. It uses the Simple DirectMedia Layer library and several other popular libraries to abstract the most common functions, making writing these programs a more intuitive task.



Installation
------------

::

   pip install pygame




Building From Source
If you want to use features that are currently in development, or you want to contribute to pygame, you will need to build pygame locally from its source code, rather than pip installing it.

Installing from source is fairly automated. The most work will involve compiling and installing all the pygame dependencies. Once that is done, run the setup.py script which will attempt to auto-configure, build, and install pygame.

Much more information about installing and compiling is available on the Compilation wiki page.


Dependencies
Pygame is obviously strongly dependent on SDL and Python. It also links to and embeds several other smaller libraries. The font module relies on SDL_ttf, which is dependent on freetype. The mixer (and mixer.music) modules depend on SDL_mixer. The image module depends on SDL_image, which also can use libjpeg and libpng. The transform module has an embedded version of SDL_rotozoom for its own rotozoom function. The surfarray module requires the Python NumPy package for its multidimensional numeric arrays. Dependency versions:

CPython >= 2.7 or PyPy >= 6.0.0 (and pypy3)
SDL >= 1.2.15
SDL_mixer >= 1.2.13
SDL_image >= 1.2.12
SDL_ttf >= 2.0.11
SDL_gfx (optional, vendored in)
NumPy >= 1.6.2 (optional)
