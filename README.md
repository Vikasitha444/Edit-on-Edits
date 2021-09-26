### 1) Start the software ###
from pywinauto.application import Application

app = Application(backend='uia').start('notepad.exe')


### 2) What is the window?  ###
window = app['Untitled - Notepad']


### 3) Get all controlers in window  ###
window.print_control_identifiers()


### 4) Type your text in type_keys area ###
window..wrapper_object().type_keys("your text",with_spaces=True)
