# mk
temporary small library using ctypes and pywin32 for mouse and keyboard emulation using windows api

# usage
```py
from _mk import Mouse, Keyboard

mouse = Mouse()
keyboard = Keyboard()

mouse.move(1000,500)
mouse.click()
keyboard.keypress('a')
```
