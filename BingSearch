import pyautogui, win32api, win32con, time, random, string
from random import randint

def random_Letters(size=7, chars=string.ascii_uppercase + string.digits):
    return ''.join(random.choice(chars) for _ in range(size))


def click(x, y):
    time.sleep(.5)
    win32api.SetCursorPos((x,y))
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTDOWN,x,y,0,0)
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTUP,x,y,0,0)
    time.sleep(.5)

def double_Click(x, y):
    win32api.SetCursorPos((x,y))
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTDOWN,x,y,0,0)
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTUP,x,y,0,0)
    time.sleep(.1)
    win32api.SetCursorPos((x,y))
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTDOWN,x,y,0,0)
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTUP,x,y,0,0)
    time.sleep(.1)

def click_Drag(x,y,a,b):
    win32api.SetCursorPos((x,y))
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTDOWN,x,y,0,0)
    time.sleep(.1)
    win32api.SetCursorPos((a,b))
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTUP,x,y,0,0)
    time.sleep(.1)

def right_Click(x,y):
    win32api.SetCursorPos((x,y))
    win32api.mouse_event(win32con.MOUSEEVENTF_RIGHTDOWN,x,y,0,0)
    win32api.mouse_event(win32con.MOUSEEVENTF_RIGHTUP,x,y,0,0)
    time.sleep(.1)
    
def virtual_Keyboard(text):
    pyautogui.typewrite(text, interval=.11)

def open_Tor():
    right_Click(212, 747)
    click(204, 668)

def maximize_Tor():
    click_Drag(494, 22, 500, 0)

def goto(website):
    click(269,49)
    virtual_Keyboard(website)
    pyautogui.press("enter")

def sign_In():
    time.sleep(15)
    click(283, 415)
    time.sleep(12)
    click(891, 271)

def Nancy():
    virtual_Keyboard("@outlook.com")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    virtual_Keyboard("pass")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("enter")

def Anthony():
    virtual_Keyboard("@outlook.com")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    virtual_Keyboard("pass")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("enter")

def Pedro():
    virtual_Keyboard("@outlook.com")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    virtual_Keyboard("pass")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("enter")

def Janet():
    virtual_Keyboard("@outlook.com")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    virtual_Keyboard("pass")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("enter")

def Steve():
    virtual_Keyboard("@outlook.com")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    virtual_Keyboard("pass")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("enter")

def Tiffany():
    virtual_Keyboard("@outlook.com")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    virtual_Keyboard("pass")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("enter")

def Julio():
    virtual_Keyboard("@outlook.com")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    virtual_Keyboard("pass")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("enter")

def Kitty():
    virtual_Keyboard("@outlook.com")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    virtual_Keyboard("pass")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("tab")
    time.sleep(.5)
    pyautogui.press("enter")
    
def three0_Searches():
    virtual_Keyboard(random_Letters())
    time.sleep(randint(1,3))
    pyautogui.press("enter")
    time.sleep(randint(1,5))
    click(397, 105)
    for i in range(7):
        pyautogui.press("backspace")
        time.sleep(.3)

def search_Bing():
    time.sleep(5)
    goto("www.bing.com")
    time.sleep(10)
    virtual_Keyboard(random_Letters())
    pyautogui.press("enter")
    time.sleep(7)
    click(397, 105)
    for i in range(7):
        pyautogui.press("backspace")
    for i in range(32):
        three0_Searches()

def switch_Accounts():
    time.sleep(1)
    click(33, 48)
    time.sleep(.8)
    click(60, 84)

def setup():
    open_Tor()
    time.sleep(7)
    maximize_Tor()
    goto("www.bing.com/rewards")
    sign_In()
    Nancy()
    search_Bing()
    switch_Accounts()

def loop(bing_Account):
    time.sleep(4)
    maximize_Tor()
    goto("www.bing.com/rewards")
    sign_In()
    bing_Account()
    search_Bing()
    switch_Accounts()

setup()
loop(Anthony)
loop(Pedro)
loop(Janet)
loop(Steve)
loop(Tiffany)
loop(Julio)
loop(Kitty)
