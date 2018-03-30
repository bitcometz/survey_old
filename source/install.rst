.. _Installation:

Installation
================================================================================

It is easy to install the survey, you just have to copy the 'survey_v*.tar.gz' to you path:
and enter commands:

	> tar -zxvf survey_v1.3.tar.gz 

Then, you have to assign the path of the survey package into you own .bashrc file, enter the above unzip folder
and enther commands:

	> sh setup.sh
	> source ~/.bashrc

And you also have to assign the path of perl bin and lib into you own .bashrc file, the following is an example:

export PATH=/NJPROJ1/PAG/Animal/software/Perl-5.18.2/bin/:$PATH (for perl)
export PERL5LIB='/NJPROJ1/PAG/Animal/software/Perl-5.18.2/lib/perl5/site_perl/5.18.2/x86_64-linux-thread-multi:/NJPROJ1/PAG/Animal/software/Perl-5.18.2/lib/perl5/site_perl/5.18.2:/NJPROJ1/PAG/Animal/software/Perl-5.18.2/lib/perl5/5.18.2/x86_64-linux-thread-multi:/NJPROJ1/PAG/Animal/software/Perl-5.18.2/lib/perl5/5.18.2' (for perl lib)



