# Horst's ebuilds

A stupid repository of my Gentoo ebuilds made specifically because
of compatibility issues, special needs, or just to resolve some bullshits.

## Adding the repository

Since this repository is not in `repos.gentoo.org`, there's 2 ways to add the repo
but I'll only be showing one.

### With eselect-repository

Install `eselect-repository` if you haven't:
```bash
sudo emerge -a app-eselect/eselect-repository
```

Add the repository with the following command:
```bash
sudo eselect repository add horsts-ebuilds git https://github.com/Horstaufmental/horsts-ebuilds.git
```

To remove the repository:
```bash
sudo eselect repository remove horsts-ebuilds
```

More information can be found [here.](https://wiki.gentoo.org/wiki/Eselect/Repository#Add_repositories)

## Other information

Most ebuilds in this repository will have a `README` file explaining when and why it was added in.

This repository are likely to be pretty quiet, depending if I ever needed to do any custom ebuilds
for a specific case, that's normal, it's meant to be my personal stuffs anyways.

All my ebuilds are licensed under **GNU General Public License v2 or later (GPLv2+)** (because it includes modifications of Gentoo's official ebuilfs)
and are provided AS IS, with no warranty whatsoever. I am NOT responsible for any kernel panics
or your hentai folder getting deleted from installing one of my ebuilds.

I don't expect any feedback or payment coming from this so just do whatever the fuck.
