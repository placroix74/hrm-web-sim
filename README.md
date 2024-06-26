# Human Resource Machine : A Simulator
An interactive, browser-based [Human Resource Machine](https://tomorrowcorporation.com/humanresourcemachine) simulator.

## Why?
The game did not come with [a level editor](https://steamcommunity.com/app/375820/discussions/0/351659808488235380/).

## Related Projects
| Project   |  Platform / Technology  |  Remarks  |
| --------- | ----------------------- | --------- |
| [eruvanos/hrm_python](https://github.com/eruvanos/hrm_python) | Desktop / Python GUI | |
| [sixlettervariables/hrmsandbox](https://github.com/sixlettervariables/hrmsandbox) | Web / node.js | No stepping controls |
| [codec-abc/human-resource-machine-program-evaluator-fable-version](https://github.com/codec-abc/human-resource-machine-program-evaluator-fable-version) | Web / node.js | No stepping controls, but all program steps can be viewed |
| [kekekawaii2839/HumanResourceMachine](https://github.com/kekekawaii2839/HumanResourceMachine) | Desktop / Qt | |
| [vncsms/HumanResourceMachine](https://github.com/vncsms/HumanResourceMachine) | Web / React.js | |
| [leroidangleterre/HumanResourceMachine](https://github.com/leroidangleterre/HumanResourceMachine) | Desktop / Java AWT | |
| [Jev-git/Godot-HumanResourceMachine](https://github.com/Jev-git/Godot-HumanResourceMachine) | Desktop / Godot | |
| [JosePedroDias/hrm](https://github.com/JosePedroDias/hrm) | Web / HTML/CSS/js | |
| [nrkn/hrm-tools](https://github.com/nrkn/hrm-tools) | Web / HTML/CSS/js | |

## Features
- Everything on _one page_ : software and help text.
- Levels load from a JSON file.
  - Every level from the original game included. (Is this legal?)

## [Live Version](https://placroix74.github.io/hrm-web-sim/hrm-web.html)

## Installation
1. [Download the current master](https://github.com/placroix74/hrm-web/archive/refs/heads/master.zip).
2. Extract and navigate to the extraction directory.
3. Launch a basic HTTP server, e.g. if you have [Python 3](https://www.python.org/downloads/) installed:
   ```
   python -m http.server [port]
   ```
   and open a browser to `locahost:<port>`, e.g.: Python `http.server`'s default port is 8000;
   _or_...
4. Open `hrm-web.html` in a browser directly; however, original game levels will not be available.

## Tech
- HTML/CSS
- JavaScript
- [jQuery](https://jquery.com/)

## Thanks
https://github.com/atesgoral/hrm-level-data

## Development
Want to contribute? Great! See [open issues](https://github.com/placroix74/hrm-web/issues).

## License

MIT

**Free Software, Hell Yeah!**
