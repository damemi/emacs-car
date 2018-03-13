# emacs-car
I have a hard time hitting the Ctrl key for all the default emacs bindings so I made some minor re-mappings using [QJoyPad](http://qjoypad.sourceforge.net/) and a [Logitech G920](https://www.amazon.com/Logitech-Dual-motor-Feedback-Driving-Responsive/dp/B00Z0UWV98). This makes my development workflow more akin to driving any manual transmission car.

Since everyone knows how to drive a car, this also provides an intuitive interface for learning emacs for new programmers, children, or people used to vim.

*Note: This is not a legal driver's education tool, and using it will not count toward any insurance or court-ordered driving courses.*

## Keymappings:
```
Steer left:        <left arrow>
Steer right:       <right arrow>
Paddle shift up:   <up arrow>
Paddle shift down: <down arrow>
Gas:               <Ctrl>
Clutch:            <Meta>
Brake:             Unmapped (speed baby)

Gears:
1st:   X
2nd:   S
3rd:   W
4th:   Y
5th:   G
6th:   <space>
R:     /
```

## Demo video

[![link to video](https://img.youtube.com/vi/fKDqTLmHzhk/0.jpg)](https://www.youtube.com/watch?v=fKDqTLmHzhk)

## Examples

1. To copy to kill ring and yank a line of text I could:
```
Gas + shift to 6th
Steer right (to select text) or Paddle shift down (to select lines)
Clutch + shift to 3rd
Paddle shift or steer to yank location
Gas + Shift to 4th
```

It's really that easy, and I can save myself from [emacs pinky](https://stackoverflow.com/questions/52492/what-is-the-best-way-to-avoid-getting-emacs-pinky) without having to do something ridiculous like map CAPS LOCK TO CTRL

## Features

* Rated Car & Driver's top safety pick for text editors
* 31 MPG and 104 WPM (highway)
* Not street legal
* Leather seats (if your office chair is leather)
* Bluetooth audio so you can take stand-up calls from your car even if you're in the office already
* Real people, not actors

## Known issues

* Brakes don't work (not a blocker)
* Can't type anything besides `X, S, W, Y, G, /, and <space>`

## Roadmap

Several development goals are set for this project, including support for automatic transmissions (Sublime text). Horn mapped to `git blame` coming next release, along with rearview mirrors that show how you should have written that feature. 