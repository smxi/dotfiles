If there are any errors in these dotfiles, please file an issue at:

https://codeberg.org/smxi/rbxi

The Codeberg repos will be mirrored to Github until the end of 2023, after that,
no updates to github repos will be made. Some time after that, the code will be
removed.

Please take the time to read this helpful article from the Software Freedom
Conservancy:

https://sfconservancy.org/GiveUpGitHub/

Any use of this project's code by GitHub Copilot, past or present, is done 
without my permission. I do not consent to GitHub's use of this project's code 
in Copilot.

=================================================================

Dotfiles and configurations.

These will be updated now and then since getting kate/geany colors
reasonably clear is an ongoing process.

Note that code editor colorschemes will focus on PHP and Perl.

Kate:
kateschema: use inport feature to import into kate code editor. 
* dark-1 is the working dark scheme. 
Global colors. Languages adjusted: Perl, Bash, PHP.
 
This will be updated routinely as it's adapted to be more usable 
than most of the default dark schemes.

* vim-dark-custom.kateschema is a modified and more readable version 
of the vim (dark) schema. Note that it is not done, unfortunately.

i3:
i3/config: save as config to either ~/.config/i3/config or /etc/i3/config
Requires i3bar and i3status. Very minimal, just the basics, for a clean 
simple i3 setup. Adjust to suite your taste, paths, and features.

Geany: 
Copy geany/vibrant-ink-2.conf  to $HOME/.config/geany/colorchemes
Copy geany/filedefs.perl to $HOME/.config/geany/filedefs
