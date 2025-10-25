---
title: Sudoku Robot
alignment: left
icon: fa-none
order: 2
---
<div style="position:relative;padding-bottom:56.25%;">
  <iframe src="https://www.youtube.com/embed/6rl6UJlCAj8" style="width:100%;height:100%;position:absolute;left:0px;top:0px;"> </iframe>  
</div>

<div style="padding-top:35px">
Just for fun, I designed and built a robot out of Legos to solve a sudoku puzzle on a touchscreen cell phone app. I started by writing a Python script to figure out the solution to any sudoku puzzle. I then built a lego carriage system capable of moving a set of touchscreen styluses to any location on the phone screen. To drive the lateral motion of the carriage and the vertical motion of the styluses, I used three Lego Mindstorms motors, one for each axis. Using an Arduino, I programmed and tuned a PD controller to provide positional control of the motors using their built-in digital encoders as a feedback signal. Upon startup, the robot determines its absolute position by moving each axis in one direction until it contacts a limit switch, indicating that it has reached a known position. After this initialization, the Python script sends touchscreen commands to the Arduino, which in turn moves the robot to enter the puzzle solution on the cell phone.
</div>