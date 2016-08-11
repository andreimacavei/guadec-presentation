% Modernising GNOME Keysign
% Andrei Macavei (`andrei.macavei89@gmail.com`), mentor: Tobias Mueller (`tobiasmue@gnome.org`)
% August 12, 2016

# Why Gnome-Keysign ?

Any text under a header 1 won't be shown. This is a title slide without
content!

---

![FOSDEM 2011 Keysign Party](fosdem2011_keysigning.jpg)


## What happened from GSoC 2015

>   - many bug fixes
>   - GPG2.1 support
>   - security improvements: MAC the entire transferred data, defend against injected QR frames.
>   - standalone non-UI key signing app
>   - openSUSE package: https://build.opensuse.org/package/show/openSUSE:Factory/gnome-keysign
>   - current release v0.6

## GSoC 2016 - Modernising Gnome-Keysign

>   - Gtk.Builder based UI (mockups by Allan Day)
>   - Flatpak app

# UI that integrates better with GNOME apps and looks more sharp

---

![Display user's keylist](keylist.png)

---

![Enter fingerprint to download key](enter_fpr.png)

# Better feedback from the user interface

---

![Key downloading phase](downloading.png)

---

![Download failed](download_failed.png)

## Flatpack App


>   - Working dependencies: setuptools, pip, py2cairo, pygobject, swig, dbus-python, gstreamer, gst-plugins-*, etc.
>   - \color{red} avahi fails to build
>   - \color{red} No webcam support for gstreamer (yet!)
>   - \color{red} Python2 support

## What's next

>   - Finish adding the remaining functionality to the new UI
>   - Have the flatpak app install easily from a repo

# Thanks for your attention!

<!--
Do math simply!

$$\sqrt{5} \neq 1$$

`Use` standard *markdown* **easily**.

### With Lower Level Headers

```python
def some_code(is_easy_to):
    integrate()

# With syntax highlighting, of course!
```
-->

