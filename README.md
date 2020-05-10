 # Description
Automate mouse clicks using image detection in current screen any number of times with python

# How it works
Dump all your images in "input_images" folder, label accordingly which image you wish to click. Code will search all available images.
Then it will automate mouse left clicks (center of image) in the order of the naming in loops, examples are included.

Example: 1_edge.png -> 2_folder.png -> 3_windows.png

# Requirements
1) Install python
2) In command prompt, enter:
   pip install pyautogui keyboard numpy opencv-python

# Custom Variables
1) max_loop: the amount of loops you want to run (default 2)
2) click_interval: interval between each mouse clicks in second (default 1)
3) loop_interval: interval between each loop in second  (default 1)

# How to run
1) Double click "custom_automation.py"
2) If you are running windows 10 OS, it will automate the mouse clicks by default examples
3) Press "Escape" to quit
4) Use sniping tool or print screen and crop any png image you wish to automate and dump to "input_images" folder.
5) Set the custom variables, start the script, run your own mouse click automation.
