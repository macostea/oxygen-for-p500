## This article covers how to use the sources ##

### Downloading ###
  1. Use this link to initialise the environment and download all the necessary packages: http://source.android.com/source/initializing.html
  1. `mkdir ~/bin`
  1. `PATH=~/bin:$PATH`
  1. `curl https://dl-ssl.google.com/dl/googlesource/git-repo/repo > ~/bin/repo`
  1. `chmod a+x ~/bin/repo`
  1. `mkdir WORKING_DIR`
  1. `cd WORKING_DIR`
  1. 
    * **For gingerbread release:**  `repo init -u git://github.com/popdog123/android_manifest.git -b gingerbread`
    * **For ICS release:**   `repo init -u git://github.com/popdog123/android_manifest.git -b ics`
  1. `repo sync`
### Building ###
  1. `. build/envsetup.sh`
  1. `lunch` -> select **oxygen\_p500** from the menu
  1. `make -j8 oxygen`
  1. your zip will be in **out/target/product/p500** named **update-oxygen-... .zip** (GB) or **update.zip** (ICS)

## WARNING ##
Just like source.android.com states, Android is best built on Ubuntu 10.04 LTS. Using newer builds of Ubuntu (or other distros) might require additional patches to the source. You can find all of them on Google.