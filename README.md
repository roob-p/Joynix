 # 🎮 GamepadToKeyboard-PlayniteExtension   
 ![GitHub Downloads](https://img.shields.io/github/downloads/roob-p/GamepadToKeyboard/total)  
 
🕹️ *Emulate mouse and keyboard input with your gamepad in a quick, easy and highly customizable manner.*  

- This extension lets you send mouse and keyboard input with your controller, so you can use it in games without gamepad support, or where some controller buttons (in particular `LT` and `RT`) do not work.  
***Perfect for old games without native controller support or with incomplete Xinput functionality.***  
**SECTION UNDER COSTRUCTION**
- Supports button toggle (key stays pressed even if the button is released)
- The program also allows fine control over several controller aspects: deadzones (per stick, axis, or direction), axis inversion and more.
- Config files can be edited and reloaded on-the-fly using a hotkey, without restarting the application.
- **In future I'll add MACRO, COMBO and TURBO functionalities. Stay tuned.**  

  # UNDER CONSTRUCTION

##### ⚠️ `GamepadToKeyboard` requires an Xinput controller (native or emulated via tools like DS4Windows, DualSenseX, x360ce, etc.).  


## ⚙️ How it works 
- Add [TOGGLE] to the button assignment to set that button as a button toggle.
- The program can also load a config if passed as parameter via command line, or by drag and drop it to `GamepadToKeyboard.exe`. Make sure that GamepadToKeyboard is disabled in Playnite, or that the target game is deactivated.


### 🔄 Live config reload

- Configuration files can be edited while the game is running.
- Just press the Hotkey (`Shift`+`Ctrl`+`5` by default) to instantly reload the current `.ini`, without restarting the application.
- The Hotkey can be customized in `GamepadToKeyboard.config`. 
<br>  


## 🕹️ Button assignments
Values you can assign to the buttons: 
- `A..Z`, `0..9`, `F1..F12`
- common buttons: `Enter`, `Space`, `Esc`, `Lalt`, `Lshift`, `Lctrl`, `Lwin`
- mouse buttons: `LBmouse`, `RBmouse`, `MBmouse`, `WheelUp`, `WheelDown`  
- Please check the bottom of this page to find the possible key assignments.

`default.ini` example:

|Button       |Keys         |‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ |Button  | Keys    |‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ |Button       |Keys        |‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ |Button       |Keys         |  
|-------------|-------------|-----------|--------|---------|-----------|-------------|------------|-----------|-------------|-------------|
|`A`          |Enter        |           |`Back`  | F1      |           |`LSup`       | W          |           |`Home`       |Esc          | 
|`B`          |Space        |           |`Start` | Esc     |           |`LSdown`     | S          |
|`X`          |Lshift       |           |`LS`    | LShift  |           |`LSleft`     | A          |            
|`Y`          |LCtrl        |           |`RS`    | MBmouse |           |`LSright`    | D          |
|`LB`         |Q            |           |`Dup`   | Up      |           |`RSup`       |            |
|`RB`         |E            |           |`Ddown` | Down    |           |`RSdown`     |            |
|`LT`         |RBmouse      |           |`Dleft` | Left    |           |`RSleft`     |            |
|`RT`         |LBmouse      |           |`Dright`| Right   |           |`RSright`    |            |


## ⚙️ Common controller options  

| Section                         | Option                         | Values / Description                                                                                                       |
|---------------------------------|--------------------------------|----------------------------------------------------------------------------------------------------------------------------|
|                                 |                                |                                                                                                                            |
|Mouse                            |AnalogToMouse                   |`1/0`    : Turn On/Off the mouse movement via analog sticks.                                                                |
|                                 |Stick 	                         |`RS/LS`  : Analog to use. Button assignments ignored.                                                                       |
|                                 |DeadzoneType                    |`1/2/4`  : Both axis/ per axis/ per direction.*                                                                             |
|                                 |(Stick)AxisInverted             |`1/0`    : Turn On/off axis inversion.                                                                                      | 
|                                 |Sensitivity                     |`value`  : Mouse movement speed.                                                                                            |
|Analogs                          |DeadzoneType                    |`1/2/4/8`: Both sticks/ per stick/ per axis/ per direction.*                                                                |    
|                                 |(Stick)AxisInverted             |`1/0`    : Turn On/off axis inversion.                                                                                      |   
|Other                            |WheelAnalogvalues               |`1/0`    : Progressive/Digital values when wheel is assigned to stick.                                                      |   
|                                 |SendKeysTypes                       |`1`: default; `2`: alternate; `3`: desktop mode (keyboard-style delay and repeat).*                                         | 
                                                                   

<br>



## ⚠️ Notes

- The program does not contain any malicious behaviour. If your AV engine flags it as malware it's a false positive. If so, please send `GamepadTokeyboard.exe` (or any associated flagged file) to your AV vendor asking for a false positive review request.


<br>  

**If you enjoy GamepadToKeyboard, you can buy me a coffee. It will be very appreciated ;)**  

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/E1E214R1KB)  

<br>


- Download last version:
<!--[v1.0.1](https://github.com/roob-p/GamepadToKeyboard/releases/download/v1.0.1/GamepadToKeyboard.exe)-->


<br>

## ⌨️ List of assignable keys
`SPACE`, `ENTER`, `ALT`, `BACKSPACE`, `BS`, `DELETE`, `DEL`, `UP`, `DOWN`, `LEFT`, `RIGHT`, `HOME`, `END`, `ESCAPE`, `ESC`, `INSERT`, `INS`, `PGUP`, `PGDN`, `F1`, `F2`, `F3`, `F4`, `F5`, `F6`, `F7`, `F8`, `F9`, `F10`, `F11`, `F12`, `TAB`, `PRINTSCREEN`, `LWIN`, `RWIN`, `NUMLOCK on`, `CAPSLOCK off`, `SCROLLLOCK toggle`, `BREAK`, `PAUSE`, `NUMPAD0`, `NUMPAD1`, `NUMPAD2`, `NUMPAD3`, `NUMPAD4`, `NUMPAD5`, `NUMPAD6`, `NUMPAD7`, `NUMPAD8`, `NUMPAD9`, `NUMPADMULT`, `NUMPADADD`, `NUMPADSUB`, `NUMPADDIV`, `NUMPADDOT`, `NUMPADENTER`, `APPSKEY`, `LALT`, `RALT`, `LCTRL`, `RCTRL`, `LSHIFT`, `RSHIFT`, `SLEEP`, `ALTDOWN`, `ALTUP`, `SHIFTDOWN`, `SHIFTUP`, `CTRLDOWN`, `CTRLUP`, `LWINDOWN`, `LWINUP`, `RWINDOWN`, `RWINUP`, `ASC nnnn`, `BROWSER_BACK`, `BROWSER_FORWARD`, `BROWSER_REFRESH`, `BROWSER_STOP`, `BROWSER_SEARCH`, `BROWSER_FAVORITES`, `BROWSER_HOME`, `VOLUME_MUTE`, `VOLUME_DOWN`, `VOLUME_UP`, `MEDIA_NEXT`, `MEDIA_PREV`, `MEDIA_STOP`, `MEDIA_PLAY_PAUSE`, `LAUNCH_MAIL`, `LAUNCH_MEDIA`, `LAUNCH_APP1`, `LAUNCH_APP2`, `OEM_102`  

<br>



### 📝 *Option notes and other settings  
|     |     |     |     |     |  
|-----|-----|-----|-----|-----|  
|**Mouse**‎  |`Deadzone`|`XDeadzone` `YDeadzone`  |`XleftDeadzone` `XrightDeadzone` `YleftDeadzone` `YrightDeadzone` |                                                                                                                                     |    
|**Analogs**‎|`Deadzone`|`LSDeadzone` `RSDeadzone`|`LSXDeadzone` `LSYDeadzone` `RSXDeadzone` `RSYDeadzone`           |`LSleftDeadzone` `LSrightDeadzone` `LSupDeadzone` `LSdownDeadzone` `RSleftDeadzone` `RSrightDeadzone` `RSupDeadzone` `RSdownDeadzone`|  

|   |  |  | |
|   -|-  |-  |- |
|**Other**|`SendKeysTypes`:|`1` Simple press (desktop single press, works well in games).                                    |`2` Continuous press on desktop, same as type 1 in games.|
||         |`3` Desktop-like behavior (keyboard-style delay and repeat). Same as the previous types in games.|`4` Desktop-alt experimental (not recommended). In-game behavior as previous types.|

|     |     |     |     |     | 
|:---:|:---:|:---:|:---:|:---:|
| `UseSameWheelSpeedLimiter`: `1\|0` -->  Use same value for WheelUp and WheelDown|`WheelSpeedLimiter`: limit scroll speed|`WheelSpeedLimiterUp`: WheelUp limiter | `WheelSpeedLimiterDown`: WheelDown limiter       |                                    |

| | | |
|-|-|-|
|**Mouse**|`SmoothFactor`:|How smooth the movement should be (1 = no smoothing, near 0 = very smooth, values below 0.1 may make the cursor too slow. 0 blocks the cursor, be cautious)|  


### 🎖️ Credits
This gamepad script was written in AutoIt.  
The program makes use of a remodified version of the XInput UDF by Oxin8 (xoninx@gmail.com) to read Xinput states.






 

