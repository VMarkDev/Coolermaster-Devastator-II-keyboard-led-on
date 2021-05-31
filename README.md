This code is used to activate the Cooler Master Devastator II keyboard light, it sends a signal to the system that the SCR LK key was pressed.
The code mentioned below must be copied to a notepad and saved as .vbs, if you want it to run automatically when you start windows you must copy the file to the home folder of the windows start menu.

Este código sirve para activar la luz del teclado Cooler Master Devastator II, envia una señal al sistema de que la tecla SCR LK fue precionado.
el codigo citado acontinuacion debe copiarlo en un block de notas y gardarlo como .vbs, si desea que se ejecute de forma automatica al iniciar windows debe copiar el archivo en la carpeta inicio del menu inicio de windows.


Code:

`Set Keys = CreateObject("WScript.Shell")

Keys.SendKeys("^{SCROLLLOCK}")`
