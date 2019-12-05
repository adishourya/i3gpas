## README

hope you liked the setup

dependencies:

- i3-resolved (gaps) for rounded corners . link:   installation instruction (commands):

- cd /path/where/you/want/the/repository

  # clone the repository
  1.git clone https://www.github.com/Airblader/i3 i3-gaps

  
  2.cd i3-gaps

  # compile & install
  3.autoreconf --force --install
  
  4.rm -rf build/
  
  5.mkdir -p build && cd build/
  

  # Disabling sanitizers is important for release versions!
  # The prefix and sysconfdir are, obviously, dependent on the distribution.
  6.  ../configure --prefix=/usr --sysconfdir=/etc --disable-sanitizers
  
  7.make
  
  8.sudo make install

  

- compton-tyrone for kwase blurring

- icon theme: taken from  u/addy-fe  openbox setup. addy-fe has the coolest setups

- theme:Archlabs-dARK

  

## screenshots



![](/home/adi/Pictures/reddit/screenshot.png)

![Screenshot_2019-05-07_20-38-27](/home/adi/Pictures/reddit/Screenshot_2019-05-07_20-38-27.png)



![](/home/adi/Pictures/reddit/Screenshot_2019-05-08_04-15-27.png)
