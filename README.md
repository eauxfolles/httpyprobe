# httpyprobe
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)

PoC/Alpha of a tool written in Python which allows to check if domains (loaded from list) are resolving, i.e. are active.

Function: Tool loads external file including names of domains (potentially identified via https://github.com/OWASP/Amass and similar tools) and probes if they are available.  

***Usage:*** "httpyprobe.py <list>"

Where: 
- "list" is the name of a file including domains (without heading http:// or https:// (located in same folder as the tool)
