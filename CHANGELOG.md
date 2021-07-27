# 2021-07-26
- Third notebook (Latent Vision).
- Some more hidden settings. Uncomment (cmd/ctrl+u) the `Very advanced settings` blocks in _Sleep_ cell to access.
- `repetition` = repeat the process for the same text for n times.
- Some minor improvements.
- Ability to batch process by entering a file path to a line-break separated txt-file in the `generate_image_of` field (untested)

# 2021-07-21
### Both notebooks
- Remove all already generated data of current execution from Drive (subdir _output_dir/id_WhatEverText_) on manual interruption (stop button or keyboardInterrupt)
---
# 2021-07-20
### Both notebooks
- Bugfix regarding lack or change of `output_dir`
- Exported progression MP4 video quality increased.
- Hidden setting to save all steps to Drive. Look for `save_all_steps` from the _Sleep_ cell in case you want to use it.
### BigSleep_crowsonkb.ipynb only
- Possibility to use random photographs from [Lorem Picsum](https://picsum.photos/) as initial/target images.
