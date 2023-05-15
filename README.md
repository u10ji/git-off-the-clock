# Off the clock

Force your commits out of key times.

## Usage

Can be used on its own by just putting it in your path and running
`off-the-clock`. Or as an alias in your .bashrc/.zshrc, like this:

```sh
function gc() { git commit -m "$@" && /bin/off-the-clock }
```

## License

This short script is under the MIT License. See [the license file](/LICENSE) for
more information.

