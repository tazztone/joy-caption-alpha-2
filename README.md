# joy-caption-alpha-2

A pinokio script to install and run the huggingface space joy-caption-alpha-two locally.

i simply cloned the original space: https://huggingface.co/spaces/fancyfeast/joy-caption-alpha-two to https://huggingface.co/spaces/tazztone/joy-caption-alpha-two and made 2 edits in app.py: deactivated `import spaces` and  `@spaces.GPU()`. and 1 edit to `requirements.txt`: added `protobuf`.
