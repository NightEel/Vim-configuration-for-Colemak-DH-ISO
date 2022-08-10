# Vim configuration for Colemak-DH ISO
If you want to use the [Colemak-DH](https://colemakmods.github.io/mod-dh/) keyboard layout on a ISO keyboard and use the original Vim Normal Mode commands (that is, you press the same key you would on the QWERTY keyboard layout, e.g. pressing the L key make the cursor move to the right instead of Vim changing to Insert Mode because the L key corresponds to i while using Colemak-DH), you can write the following on your `~/.vimrc`:
<pre>
nnoremap m h
nnoremap n j
nnoremap e k
nnoremap i l
nnoremap l u
nnoremap u i
nnoremap y o
nnoremap j y
nnoremap b t
nnoremap p r
nnoremap f e
nnoremap r s
nnoremap s d
nnoremap t f
nnoremap d c
nnoremap c x
nnoremap x z
nnoremap \ b
nnoremap h m
nnoremap k n
</pre>

Of course you can use `nnoremap` with other commands too. It's better to use `nnoremap` instead of `nmap` because the first one avoids recursive mapping.

## Note
It's not finished yet, changes are about to come.
