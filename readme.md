
## Setup multiple public project

Install the `repo` utility:
---------------------------
To use this manifest repo, the `repo` tool must be installed first.
```
    $ mkdir -p ~/.bin
    $ PATH="${HOME}/.bin:${PATH}"
    $ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.bin/repo
    $ chmod a+rx ~/.bin/repo
```

Add Path
------------------------------
  1. Windows > Add path to environment system variable path "C:\Users\Administrator\.bin"
  2. Linux   > Add path to ~/.bashrc & source ~/.bashrc [sudo apt-get install repo]

Download Repo Projects
------------------------------
```
$: mkdir <projects>
$: cd <projects>
$: repo init -u https://github.com/savaliyadnk/repo-manifest.git -b main
$: repo sync
```

## Reference
  1. https://git-repo.info/en/docs/multi-repos/overview/
  2. https://github.com/nxp-imx/imx-manifest/blob/imx-linux-mickledore/imx-6.1.22-2.0.0.xml
