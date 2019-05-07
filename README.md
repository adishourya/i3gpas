## README

hope you liked the setup

dependencies:

- i3-resolved (gaps) for rounded corners . link:   installation instruction (commands):

- cd /path/where/you/want/the/repository

  # clone the repository
  git clone https://www.github.com/Airblader/i3 i3-gaps

  

  cd i3-gaps

  # compile & install
  autoreconf --force --install
  rm -rf build/
  mkdir -p build && cd build/

  # Disabling sanitizers is important for release versions!
  # The prefix and sysconfdir are, obviously, dependent on the distribution.
  ../configure --prefix=/usr --sysconfdir=/etc --disable-sanitizers
  make
  sudo make install

  

- compton-tyrone for kwase blurring

- icon theme: taken from  u/addy-fe  openbox setup. addy-fe has the coolest setups

- theme:Archlabs-dARK

  

## screenshots



![](/home/adi/Pictures/reddit/screenshot.png)

![Screenshot_2019-05-07_20-38-27](/home/adi/Pictures/reddit/Screenshot_2019-05-07_20-38-27.png)



![](/home/adi/Pictures/reddit/Screenshot_2019-05-08_04-15-27.png)