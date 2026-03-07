AC_INIT([Text Processing Tools], [0.2])

AC_PROG_AWK

AC_PATH_PROG([PERL], [perl])
AX_PROG_PERL_MODULES([File::Temp], [], [AC_MSG_WARN([Perl module File::Temp was not found. Some tools wont work without it.])])
AX_PROG_PERL_MODULES([Getopt::Long], [], [AC_MSG_WARN([Perl module Getopt::Long was not found. Some tools wont work without it.])])

AM_SILENT_RULES([yes])
AM_INIT_AUTOMAKE([foreign])
AC_CONFIG_FILES([lblmp unstruct multidoc fsplit multidocw workonw 2fw])
AC_CONFIG_FILES([Makefile])

AC_OUTPUT
