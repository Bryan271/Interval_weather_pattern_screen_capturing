# Review Notes (2026-03-11)

## Overview
- Repo clones successfully.
- Contains Tkinter GUI, Selenium modules, scheduler, logging stub.
- README outlines features and dependencies.

## Observations
1. `selenium_module.py` hardcodes screenshot directory; add config.
2. Logger referenced but not shown (likely simple wrapper).
3. Chrome webdriver invoked without options (may need driver path env var).
4. Scheduler uses `root.after`; workflow is synchronous but adequate for prototype.

## Suggestions
- Externalize link list and counters to config file.
- Add requirements.txt for Selenium/Tkinter versions.
- Consider headless Chrome option for non-GUI environments.
