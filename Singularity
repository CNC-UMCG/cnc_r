Bootstrap: shub
From: CNC-UMCG/cnc_base


%post
        apt-get install -y software-properties-common
 	echo "deb http://cran.rstudio.com/bin/linux/ubuntu xenial/" | tee -a /etc/apt/sources.list
	gpg --keyserver keyserver.ubuntu.com --recv-key E084DAB9
	gpg -a --export E084DAB9 | apt-key add -

	apt-get update

	apt-get install -y r-base r-base-dev

