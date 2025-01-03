# litter

A simple CLI tool to upload temporary files to [Litterbox](https://litterbox.catbox.moe/)/[Catbox](https://catbox.moe/). You type a command, you get a link. As simple as that!

Made for those who are too lazy to open SCP/SFTP.

## Installation
```
pip install pylitter
```

or use `pipx` if you're on Arch or equivalent.
## Usage
The main command is "throw", because just "**throw it into the litter, man**". Geddit?

```
throw file (for|forever) [1h/12h/24h/72h]
```

- Use `for <time>` if you want to upload to Litterbox, temporary.
- Use `forever` if you want to upload to Catbox, permanent.

>[!NOTE]
>The old command `litter` and the new `throw` can still be used interchangeably, but it is recommended to use the superior `throw`.

>[!IMPORTANT]
>Remember that Catbox has a file size limit of 200mb.

## Examples

```
throw test.jpg for 12h   

[71097/71097] bytes |====================>|
Your link : https://litter.catbox.moe/zmr6i6.jpg
```

```
throw test2.jpg forever

[23039/23039] bytes |====================>|
Your link : https://files.catbox.moe/nxulxl.jpg
```

## Acknowledgements
- [@yukinotenshi](https://github.com/yukinotenshi) for creating [PyUpload](https://github.com/yukinotenshi/pyupload).
- [catbox.llc](https://catbox.llc/) for litterbox and catbox. 

You guys are amazing!
## Contributing
If you wish to, you can contribute to the project by submitting a pull request.

The best way to contribute would be to suggest the developer a provider or a feature, more better if you can show a logic of how that can be done, you'll be mentioned and thanked!
### Sponsoring
Money is appreciated, but **stars even more**! Feel free to star the project if you think it is worthy of one. Moreover, you can just talk, banter and argue with the developer as that way you'll be paying with your time.

<p align="center"><sup>Never forget, you are SUPER cool!</sup></p>
