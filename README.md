report-progress-statistic
=========================

Report a progress in a program listing.

For example:

rlucca@darkin / $ report ls .<BR />
&nbsp;&nbsp;Applications<BR />
&nbsp;&nbsp;Developer<BR />
&nbsp;&nbsp;Library<BR />
&nbsp;&nbsp;Network<BR />
&nbsp;&nbsp;System<BR />
&nbsp;&nbsp;Users<BR />
&nbsp;&nbsp;Volumes<BR />
&nbsp;&nbsp;bin<BR />
&nbsp;&nbsp;cores<BR />
&nbsp;&nbsp;dev<BR />
&nbsp;&nbsp;etc<BR />
&nbsp;&nbsp;home<BR />
&nbsp;&nbsp;mach_kernel<BR />
&nbsp;&nbsp;net<BR />
&nbsp;&nbsp;opt<BR />
&nbsp;&nbsp;private<BR />
&nbsp;&nbsp;sbin<BR />
&nbsp;&nbsp;sw<BR />
&nbsp;&nbsp;tmp<BR />
&nbsp;&nbsp;usr<BR />
&nbsp;&nbsp;var<BR />

rlucca@darkin / $ report ls .<BR />
&nbsp;&nbsp;[  4%] Applications<BR />
&nbsp;&nbsp;[  9%] Developer<BR />
&nbsp;&nbsp;[ 14%] Library<BR />
&nbsp;&nbsp;[ 19%] Network<BR />
&nbsp;&nbsp;[ 23%] System<BR />
&nbsp;&nbsp;[ 28%] Users<BR />
&nbsp;&nbsp;[ 33%] Volumes<BR />
&nbsp;&nbsp;[ 38%] bin<BR />
&nbsp;&nbsp;[ 42%] cores<BR />
&nbsp;&nbsp;[ 47%] dev<BR />
&nbsp;&nbsp;[ 52%] etc<BR />
&nbsp;&nbsp;[ 57%] home<BR />
&nbsp;&nbsp;[ 61%] mach_kernel<BR />
&nbsp;&nbsp;[ 66%] net<BR />
&nbsp;&nbsp;[ 71%] opt<BR />
&nbsp;&nbsp;[ 76%] private<BR />
&nbsp;&nbsp;[ 80%] sbin<BR />
&nbsp;&nbsp;[ 85%] sw<BR />
&nbsp;&nbsp;[ 90%] tmp<BR />
&nbsp;&nbsp;[ 95%] usr<BR />
&nbsp;&nbsp;[100%] var<BR />

Other example:

rlucca@darkin /tmp/hellow $ report make<BR />
&nbsp;&nbsp;cc -c -o hello.o hello.c<BR />
&nbsp;&nbsp;cc hello.o -o hello<BR />
&nbsp;&nbsp;./hello<BR />
&nbsp;&nbsp;hello world<BR />
&nbsp;&nbsp;rm hello hello.o<BR />

rlucca@darkin /tmp/hellow $ report make<BR />
&nbsp;&nbsp;[ 20%] cc    -c -o hello.o hello.c<BR />
&nbsp;&nbsp;[ 40%] cc   hello.o   -o hello<BR />
&nbsp;&nbsp;[ 60%] ./hello<BR />
&nbsp;&nbsp;[ 80%] hello world<BR />
&nbsp;&nbsp;[100%] rm hello hello.o<BR />



Dependencies
============

It just uses these commands:<BR />
	- md5 / md5sum<BR />
	- echo, printf<BR />
	- cut, read, cat<BR />
