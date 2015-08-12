Brandy 1.20.1 + [brandy-osx-sdl-support.patch](http://sourceforge.net/p/brandy/patches/9/)
--------------------------------------------

This version uses the [SDL](http://www.libsdl.org/) graphics library.
The file `docs/history` lists what has been done.

![graphdemo.bas](http://assets.c7.se/skitch/Brandy_Basic_V_Interpreter_-_graphdemo.bas-20141026-120928.png)
![pastriang.bas](http://assets.c7.se/skitch/Brandy_Basic_V_Interpreter_-_pastriang.bas-20141026-120124.png)

## Dependencies

You need to have SDL installed in order to compile Brandy.

```
brew install sdl
```

## Compilation

GUI version: `make nodebug`
CLI version: `make nodebug GUI=console`

## Installation

Just copy the compiled binaries to somewhere in your `PATH`

## Files

Filename          | Description
:---------------- | :---------------------------------------------------
`docs/`           | Documentation
`examples/`       | Some sample programs
`COPYING`         | Copy of GPL
`src/`            | Directory containing source code
`Makefile`        | Makefile to compile brandy under OS X

## License

> The program is distributed under the terms of the GNU GPL.
>
> Brandy is free software; you can redistribute it and/or modify it
> under the terms of the GNU General Public License as published by
> the Free Software Foundation; either version 2, or (at your
> option) any later version.
>
> Brandy is distributed in the hope that it will be useful, but
> WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
> General Public License for more details.
>
> You should have received a copy of the GNU General Public License
> along with Brandy; see the file COPYING.  If not, write to
> the Free Software Foundation, 59 Temple Place - Suite 330,
> Boston, MA 02111-1307, USA.
