# xdkim - fork of libdkim 1.0.21

xdkim  was forked of libdkim-1.0.21.  The libdkim project is/was marked
as inactive on sourceforge in 2016. At time libdkim-1.0.21 was the last 
version available.

Initial the code was stripped down, all WIN32 stuff was (hopefully) re-
moved. The shared library functionality is gone.  The library is linked
statically with the executable xdkim, which is the renamed successor of
the former libdkimtest.

xdkim was tested to run on Linux-like systems only.
