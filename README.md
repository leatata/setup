setup.git
=========
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure both the machine and your individual development environment as
follows:

```sh
cd $HOME
sudo apt-get install -y git-core
git clone https://github.com/leatata/setup.git
./setup/setup.sh (for normal Node environment)
./setup/setup_meteor.sh (for meteor Environment)
```

See also http://github.com/leatata/dotfiles






