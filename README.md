# vnano

Mighty nano inside a vim.

I initially wrote this for a parody hackathon, and now
I just want to see how far I can go with this.

[vim8 support blog post](https://nims11.github.io/blog/vim-nano)

# Features

- Looks like GNU nano
- Various nano shortcuts/features
- No Normal/Insert mode

# Requirements

- neovim/vim8 (terminal support abused to replicate nano interface)
- python (should work with 2 or 3, I only test it on py3 nowadays)

# Installation

RHEL8
```
$ sudo yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
$ sudo yum install -y neovim python3-neovim
```

Clone the repo to /opt
```
$ cd /opt
$ sudo git clone https://github.com/Network-Ansible/vim-nano.git
```

Alias to .bashrc
```
$ echo "alias vnano='nvim -u /opt/vim-nano/nano.vim'" >> ~/.bashrc
```

![vim-nano in action](https://raw.githubusercontent.com/nims11/vim-nano/master/screenshot.png)
