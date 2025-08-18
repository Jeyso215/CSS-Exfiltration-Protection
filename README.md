# CSS Exfil Protection

CSS Exfil Protection extension for Chrome.

Information about the plugins and the CSS Exfil attack can be found here:
* [Stealing Data With CSS: Attack and Defense](https://www.mike-gualtieri.com/posts/stealing-data-with-css-attack-and-defense)
* [CSS Exfil Vulnerability Tester](https://www.mike-gualtieri.com/css-exfil-vulnerability-tester)
* [CSS Exif Protection POC Tester](https://randshell.github.io/CSS-Exfil-Protection-POC/)

### How To Test

Go to any website and go into ```Inspect Element``` and then ```Console/Network```. You can also due to this by press ```F12```.

## Issues

- Like ```UBlockOrigin``` it has to stay on "Manifest v2" due to Manifest v3 limitations. See [here](https://github.com/mlgualtieri/CSS-Exfil-Protection/issues/41#issuecomment-3194432557)
- Enable ```Manifest v2``` Legacy and further support on Brave. To do this, go into ```brave://flags``` and type ```Manifest v2``` and enable the 2 options.

### Screenshot

![](https://files.catbox.moe/qrptjk.png)

### Contributing

If reporting bugs please include the steps to replicate.  Useful information includes:
* URL which triggers the error
* Expected result
* Actual result

### Credits

- [mlgualtieri](https://github.com/mlgualtieri) - Original Developer
- [Jeyso215](https://github.com/Jeyso215) - New maintainer
- [randshell](https://github.com/randshell) - Vulnerability disclosure
