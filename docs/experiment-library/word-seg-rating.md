# Word Segmentation (Rating)

This is the word segmentation task from Saffran, Aslin & Newport (1996). This is the shorter version of the exposure (2 minutes) that was used for the baby experiments.  In the Newport lab, it is often called "Baby Saffran".



## params.yaml

### experiment_wide

 Parameter | Type | Description
 ---|---|---
`fullscreen` | boolean | If `true`, enter fullscreen mode; if `false`, leave fullscreen mode.
`show_progress_bar` | boolean | If `true`, show experiment progress bar; if `false`, hide progress bar.
`images_to_preload` | YAML list | List images to preload. Use `None` if no images to preload.
`sounds_to_preload` | YAML list | List sounds to preload. Use `None` if no sounds to preload.

### instructions

Parameter | Type | Description
---|---|---
`timing_post_trial` | Value | Time.
`data` | ?? | ??
`pages` | YAML list | desc.
`key_forward` | ?? | ??
`key_backward` | ?? | ??
`allow_backward` | ?? | ??
`allow_keys` | ?? | ??
`show_clickable_nav` | boolean | If `true`, show experiment progress bar; if `false`, hide progress bar.

### exposure

Parameter | Type | Description
---|---|---
`stimulus` | Value | Time.
`trial_ends_after_audio` | ?? | ??

### test

Parameter | Type | Description
---|---|---
`timeline` | Value | Time.
`post_trial_gap` | ?? | ??
`choices` | Value | Time.
`prompt` | ?? | ??
`response_ends_trial` | ?? | ??
