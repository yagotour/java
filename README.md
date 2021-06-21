sudo apt update

sudo apt install apt-transport-https software-properties-common gnupg wget

wget -qO - https://adoptopenjdk.jfrog.io/adoptopenjdk/api/gpg/key/public | sudo apt-key add -

sudo add-apt-repository https://adoptopenjdk.jfrog.io/adoptopenjdk/deb/

sudo apt update

sudo apt install adoptopenjdk-16-hotspot
