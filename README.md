Install from installation file
modify  File "/workspace/DINO/util/slconfig.py", line 317, in pretty_text
    text, _ = FormatCode(text, style_config=yapf_style, verify=True)
TypeError: FormatCode() got an unexpected keyword argument 'verify'
Remove 'verify=True'

Modify file from np.float to float

