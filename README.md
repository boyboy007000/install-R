# install-R

add deb http://<favourite-cran-mirror>/bin/linux/debian jessie-cran35/
at /etc/apt/sources.list
apt-key adv --keyserver keys.gnupg.net --recv-key 'E19F5F87128899B192B1A2C2AD5F960A256A04AF'
apt-get update
apt-get install r-base (r-base-dev in dev)
ref :https://cran.r-project.org/
