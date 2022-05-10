# Brick Breaker
___
We used the base code from Lab 6 and modified it to make a Brick Breaker program.

Source Files:

- adc_if.vhd
- bat_n_ball.vhd
- clk_wiz_0.vhd
- clk_wiz_0_clk_wiz.vhd
- leddec16.vhd
- pong.vhd
- vga_sync.vhd

Constraint Files:

- pong.xcd
___

### To Run:
#### 1. Create a new RTL Project in Vivado
- Create 7 new source files named: *adc_if.vhd, bat_n_ball.vhd, clk_wiz_0.vhd, clk_wiz_0_clk_wiz.vhd, leddec16.vhd, pong.vhd, vga_sync.vhd*
- Create 1 new constraint file named: *pong.xcd*
- Choose Nexys A7-100T board for the project
- Copy code from all source and constraint files into the project files
#### 2. Run Synthesis
#### 3. Run Impelementation
#### 4. Generate Bitstream
#### 5. Open Hardware Manager
- Click auto connect
#### 6. Program Device
- select bitstream you just generated
#### 7. Enjoy!
- Make sure to flip one of the first switches on the right to avoid setting the ball speed to 0 at the start
___

### Modifications:
All changes made to the program from Lab 6 were made in the bat_n_ball.vhd file
- Signal created for each brick
- Position set for each brick
- color scheme set for bat, ball, and bricks
- process to draw for each brick
- hit detection for each brick

Possible changes for the future
- change counter to brick hit rather than bat hit
- fix hit detection and bounce from top of brick
- add respawning bricks
- add a reset bricks button
___
### Results:
![](https://github.com/dsmith15/CPE487-DSD/blob/main/Final%20Project%20-%20Brick%20Breaker/IMG-9649.jpg)
![](https://github.com/dsmith15/CPE487-DSD/blob/main/Final%20Project%20-%20Brick%20Breaker/Brick%20breaker%20Gif.gif)
