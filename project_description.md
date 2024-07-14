# Project Description

This project is a comprehensive application designed to run on a Macropad. It includes various apps that provide different functionalities such as media controls, navigation, and more. The project is structured to be modular, with each app encapsulated in its own file, making it easy to manage and extend.

## Project Map

```
.github/
  workflows/
    pre-commit.yaml

apps/
  chrome.py
  func.py
  home.py
  nav.py
  numpad.py
  spotify.py
  switcher.py
  window.py

lib/
  adafruit_bitmap_font/
    __init__.py
    bdf.mpy
    bitmap_font.mpy
    glyph_cache.mpy
    pcf.mpy
    ttf.mpy
  adafruit_debouncer.mpy
  adafruit_display_shapes/
    __init__.py
    arc.mpy
    circle.mpy
    line.mpy
    multisparkline.mpy
    polygon.mpy
    rect.mpy
    roundrect.mpy
    sparkline.mpy
    triangle.mpy
  adafruit_display_text/
    __init__.mpy
    bitmap_label.mpy
    label.mpy
    outlined_label.mpy
    scrolling_label.mpy
  adafruit_hid/
    __init__.mpy
    consumer_control.mpy
    consumer_control_code.mpy
    keyboard.mpy
    keyboard_layout_base.mpy
    keyboard_layout_us.mpy
    keycode.mpy
    mouse.mpy
  adafruit_macropad.mpy
  adafruit_midi/
    __init__.mpy
    channel_pressure.mpy
    control_change.mpy
    control_change_values.mpy
    midi_continue.mpy
    midi_message.mpy
    mtc_quarter_frame.mpy
    note_off.mpy
    note_on.mpy
    pitch_bend.mpy
    polyphonic_key_pressure.mpy
    program_change.mpy
    start.mpy
    stop.mpy
    system_exclusive.mpy
    timing_clock.mpy
  adafruit_pixelbuf.mpy
  adafruit_simple_text_display.mpy
  adafruit_ticks.mpy
  neopixel.mpy

utils/
  __init__.py
  app_pad.py
  apps/
    __init__.py
    base.py
    key.py
  commands.py
  constants.py
  settings.py

.gitignore
.pre-commit-config.yaml
README.md
code.py
default_settings.py
pyproject.toml
```
