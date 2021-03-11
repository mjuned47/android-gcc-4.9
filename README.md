# gcc-4.9-patch

Fix ‘const char* libc_name_p(const char*, unsigned int)’ redeclared inline with ‘gnu_inline’ attribute

Move this four files to

gcc_source/gcc/cp/Make-lang.in

    "    /gcc/cp/except.c

    "    /gcc/cp/cfns.gperf

    "    /gcc/cp/cfns.h
