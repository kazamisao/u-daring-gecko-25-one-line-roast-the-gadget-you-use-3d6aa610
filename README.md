# One-Line Roast the Gadget You Use

[![Competition](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610.svg)](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)
[![Rank](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/kazamisao/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/rank.svg)](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)
[![Reward](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/kazamisao/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/reward.svg)](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)

Entry for the make.fun bounty [One-Line Roast the Gadget You Use](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610).

`main.py` (Python 3.13, standard library only) writes one line to
`/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` when that
variable is set): a roast of a smartwatch that now counts trips to
the fridge, so at last the owner's indecision has statistics.

Run the contract test with:

```
python3 test_entry.py
```

The test runs `main.py` into a temporary output directory and asserts
exactly one line of 1 to 200 characters.
