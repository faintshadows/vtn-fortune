a fortune-mod pack with quotes from a vintage rare telegram group

I wanted a somewhat easy way to get used to using git/GitHub, without
needing to also know how to code. So I decided to make my sticker pack
of a vintage rare telegram group into fun fortune-mod fortunes.

**Hey watch out, many of these fortunes are lewd/explicit in nature**
Like, a lot of them. I did not expect there to be that many when
I did this. The nsfw fortunes are in the `off/vtn` file.
(As of now, in my testing `fortune` won't pick any from the `off/vtn` file,
you have to specify it manually.)

## To Install
For me, on Gentoo, the fortunes are located at `/usr/share/fortune`.
On Debian, it seems to be located at `/usr/share/games/fortunes`.
Just drop the two files (`vtn`, `vtn.dat`) in there, and just running
`fortune` should pull it up at random. Same goes for the two files in
the `off` directory.

If you just want to get these fortunes, have the two files in your
current working directory, and do `fortune vtn`.

## Contributing
To add your own quotes to the file, just clone the repo, and edit `vtn`.
Quotes are separated by the `%` symbol, which goes on its own line.

The `vtn.dat` file is updated with `strfile vtn`.

Since there are multiple sources of quotes, the ordering of the file
will differ and likely I will just remake my own .dat with my master
copy of the file. Try not to include it in PRs, it's no use to me.
