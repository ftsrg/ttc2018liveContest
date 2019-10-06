# Visualization

Install R and pandoc. For Ubuntu 16.04+, the following works:

```console
sudo apt install -y r-base r-base-dev pandoc
# for tidyverse
sudo apt install -y libssl-dev libxml2-dev libcurl4-openssl-dev
```

Run R and install the [Tidyverse](https://www.tidyverse.org/) package:

```R
install.packages("tidyverse")
```

(This [might fail](https://github.com/FTSRG/cheat-sheets/wiki/R-programming-language#installing-tidyverse-on-ubuntu) if you haven't installed the second group of packages, `rvest`, `xml2`, .etc.)

To generate the plot, use the Makefile:

```console
make
```