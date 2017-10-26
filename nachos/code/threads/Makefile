# NOTE: this is a GNU Makefile.  You must use "gmake" rather than "make".
#
# Makefile for the threads assignment.  The threads assignment must
#  be done first!
#
# Copyright (c) 1992 The Regents of the University of California.
# All rights reserved.  See copyright.h for copyright notice and limitation 
# of liability and disclaimer of warranty provisions.

DEFINES = -DTHREADS
INCPATH = -I../threads -I../machine
HFILES = $(THREAD_H)
CFILES = $(THREAD_C)
C_OFILES = $(THREAD_O)

include ../Makefile.common
include ../Makefile.dep
#-----------------------------------------------------------------
# DO NOT DELETE THIS LINE -- make depend uses it
# DEPENDENCIES MUST END AT END OF FILE
main.o: ../threads/main.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/fstream \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/istream \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ios \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/iosfwd \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/c++config.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/os_defines.h \
 /usr/include/features.h /usr/include/sys/cdefs.h \
 /usr/include/bits/wordsize.h /usr/include/bits/long-double.h \
 /usr/include/gnu/stubs.h /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/cpu_defines.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stringfwd.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/memoryfwd.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/postypes.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/cwchar \
 /usr/include/wchar.h /usr/include/bits/libc-header-start.h \
 /usr/include/stdio.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/xlocale.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/exception \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/atomic_lockfree_defines.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/char_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_algobase.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/functexcept.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/exception_defines.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/cpp_type_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/type_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/numeric_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_pair.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/move.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/concept_check.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_iterator_base_types.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_iterator_base_funcs.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/debug/debug.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_iterator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/ptr_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/predefined_ops.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/localefwd.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/c++locale.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/clocale \
 /usr/include/locale.h /usr/include/bits/locale.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/cctype \
 /usr/include/ctype.h /usr/include/bits/types.h \
 /usr/include/bits/typesizes.h /usr/include/endian.h \
 /usr/include/bits/endian.h /usr/include/bits/byteswap.h \
 /usr/include/bits/byteswap-16.h /usr/include/bits/uintn-identity.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/ios_base.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/atomicity.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/gthr.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/gthr-default.h \
 /usr/include/pthread.h /usr/include/sched.h \
 /usr/include/bits/types/time_t.h \
 /usr/include/bits/types/struct_timespec.h /usr/include/bits/sched.h \
 /usr/include/time.h /usr/include/bits/time.h /usr/include/bits/timex.h \
 /usr/include/bits/types/struct_timeval.h \
 /usr/include/bits/types/clock_t.h /usr/include/bits/types/struct_tm.h \
 /usr/include/bits/types/clockid_t.h /usr/include/bits/types/timer_t.h \
 /usr/include/bits/types/struct_itimerspec.h \
 /usr/include/bits/pthreadtypes.h /usr/include/bits/setjmp.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/atomic_word.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/locale_classes.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/string \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/allocator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/c++allocator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/new_allocator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/new \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/ostream_insert.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/cxxabi_forced.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_function.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/backward/binders.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/range_access.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/basic_string.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/alloc_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/basic_string.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/locale_classes.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/stdexcept \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/streambuf \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/streambuf.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/basic_ios.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/locale_facets.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/cwctype \
 /usr/include/wctype.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/ctype_base.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/streambuf_iterator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/ctype_inline.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/locale_facets.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/basic_ios.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ostream \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/ostream.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/istream.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/codecvt.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/cstdio \
 /usr/include/libio.h /usr/include/_G_config.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/basic_file.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/c++io.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/fstream.tcc \
 ../threads/utility.h ../machine/sysdep.h ../threads/copyright.h \
 /usr/include/string.h ../threads/system.h ../threads/thread.h \
 ../threads/scheduler.h ../threads/list.h ../machine/interrupt.h \
 ../threads/list.h ../machine/stats.h ../machine/timer.h \
 ../threads/utility.h
list.o: ../threads/list.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../threads/list.h ../threads/utility.h \
 ../machine/sysdep.h ../threads/copyright.h /usr/include/stdio.h \
 /usr/include/bits/libc-header-start.h /usr/include/features.h \
 /usr/include/sys/cdefs.h /usr/include/bits/wordsize.h \
 /usr/include/bits/long-double.h /usr/include/gnu/stubs.h \
 /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h
scheduler.o: ../threads/scheduler.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../threads/scheduler.h ../threads/list.h \
 ../threads/utility.h ../machine/sysdep.h ../threads/copyright.h \
 /usr/include/stdio.h /usr/include/bits/libc-header-start.h \
 /usr/include/features.h /usr/include/sys/cdefs.h \
 /usr/include/bits/wordsize.h /usr/include/bits/long-double.h \
 /usr/include/gnu/stubs.h /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h ../threads/thread.h \
 ../threads/system.h ../machine/interrupt.h ../threads/list.h \
 ../machine/stats.h ../machine/timer.h ../threads/utility.h
synch.o: ../threads/synch.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../threads/synch.h ../threads/thread.h \
 ../threads/utility.h ../machine/sysdep.h ../threads/copyright.h \
 /usr/include/stdio.h /usr/include/bits/libc-header-start.h \
 /usr/include/features.h /usr/include/sys/cdefs.h \
 /usr/include/bits/wordsize.h /usr/include/bits/long-double.h \
 /usr/include/gnu/stubs.h /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h ../threads/list.h \
 ../threads/system.h ../threads/scheduler.h ../machine/interrupt.h \
 ../threads/list.h ../machine/stats.h ../machine/timer.h \
 ../threads/utility.h
synchlist.o: ../threads/synchlist.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../threads/synchlist.h ../threads/list.h \
 ../threads/utility.h ../machine/sysdep.h ../threads/copyright.h \
 /usr/include/stdio.h /usr/include/bits/libc-header-start.h \
 /usr/include/features.h /usr/include/sys/cdefs.h \
 /usr/include/bits/wordsize.h /usr/include/bits/long-double.h \
 /usr/include/gnu/stubs.h /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h ../threads/synch.h \
 ../threads/thread.h
system.o: ../threads/system.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../threads/system.h ../threads/utility.h \
 ../machine/sysdep.h ../threads/copyright.h /usr/include/stdio.h \
 /usr/include/bits/libc-header-start.h /usr/include/features.h \
 /usr/include/sys/cdefs.h /usr/include/bits/wordsize.h \
 /usr/include/bits/long-double.h /usr/include/gnu/stubs.h \
 /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h ../threads/thread.h \
 ../threads/scheduler.h ../threads/list.h ../machine/interrupt.h \
 ../threads/list.h ../machine/stats.h ../machine/timer.h \
 ../threads/utility.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/fstream \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/istream \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ios \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/iosfwd \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/c++config.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/os_defines.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/cpu_defines.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stringfwd.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/memoryfwd.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/postypes.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/cwchar \
 /usr/include/bits/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/exception \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/atomic_lockfree_defines.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/char_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_algobase.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/functexcept.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/exception_defines.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/cpp_type_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/type_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/numeric_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_pair.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/move.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/concept_check.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_iterator_base_types.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_iterator_base_funcs.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/debug/debug.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_iterator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/ptr_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/predefined_ops.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/localefwd.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/c++locale.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/clocale \
 /usr/include/locale.h /usr/include/bits/locale.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/cctype \
 /usr/include/ctype.h /usr/include/endian.h /usr/include/bits/endian.h \
 /usr/include/bits/byteswap.h /usr/include/bits/byteswap-16.h \
 /usr/include/bits/uintn-identity.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/ios_base.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/atomicity.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/gthr.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/gthr-default.h \
 /usr/include/pthread.h /usr/include/sched.h \
 /usr/include/bits/types/time_t.h \
 /usr/include/bits/types/struct_timespec.h /usr/include/bits/sched.h \
 /usr/include/time.h /usr/include/bits/time.h /usr/include/bits/timex.h \
 /usr/include/bits/types/struct_timeval.h \
 /usr/include/bits/types/clock_t.h /usr/include/bits/types/struct_tm.h \
 /usr/include/bits/types/clockid_t.h /usr/include/bits/types/timer_t.h \
 /usr/include/bits/types/struct_itimerspec.h \
 /usr/include/bits/pthreadtypes.h /usr/include/bits/setjmp.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/atomic_word.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/locale_classes.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/string \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/allocator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/c++allocator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/new_allocator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/new \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/ostream_insert.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/cxxabi_forced.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/stl_function.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/backward/binders.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/range_access.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/basic_string.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ext/alloc_traits.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/basic_string.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/locale_classes.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/stdexcept \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/streambuf \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/streambuf.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/basic_ios.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/locale_facets.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/cwctype \
 /usr/include/wctype.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/ctype_base.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/streambuf_iterator.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/ctype_inline.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/locale_facets.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/basic_ios.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/ostream \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/ostream.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/istream.tcc \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/codecvt.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/cstdio \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/basic_file.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/x86_64-pc-linux-gnu/bits/c++io.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/c++/bits/fstream.tcc
thread.o: ../threads/thread.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../threads/thread.h ../threads/utility.h \
 ../machine/sysdep.h ../threads/copyright.h /usr/include/stdio.h \
 /usr/include/bits/libc-header-start.h /usr/include/features.h \
 /usr/include/sys/cdefs.h /usr/include/bits/wordsize.h \
 /usr/include/bits/long-double.h /usr/include/gnu/stubs.h \
 /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h ../threads/switch.h \
 ../threads/synch.h ../threads/list.h ../threads/system.h \
 ../threads/scheduler.h ../machine/interrupt.h ../threads/list.h \
 ../machine/stats.h ../machine/timer.h ../threads/utility.h
utility.o: ../threads/utility.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../threads/utility.h ../machine/sysdep.h \
 ../threads/copyright.h /usr/include/stdio.h \
 /usr/include/bits/libc-header-start.h /usr/include/features.h \
 /usr/include/sys/cdefs.h /usr/include/bits/wordsize.h \
 /usr/include/bits/long-double.h /usr/include/gnu/stubs.h \
 /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h
threadtest.o: ../threads/threadtest.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../threads/system.h ../threads/utility.h \
 ../machine/sysdep.h ../threads/copyright.h /usr/include/stdio.h \
 /usr/include/bits/libc-header-start.h /usr/include/features.h \
 /usr/include/sys/cdefs.h /usr/include/bits/wordsize.h \
 /usr/include/bits/long-double.h /usr/include/gnu/stubs.h \
 /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h ../threads/thread.h \
 ../threads/scheduler.h ../threads/list.h ../machine/interrupt.h \
 ../threads/list.h ../machine/stats.h ../machine/timer.h \
 ../threads/utility.h
interrupt.o: ../machine/interrupt.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../machine/interrupt.h ../threads/list.h \
 ../threads/copyright.h ../threads/utility.h ../machine/sysdep.h \
 /usr/include/stdio.h /usr/include/bits/libc-header-start.h \
 /usr/include/features.h /usr/include/sys/cdefs.h \
 /usr/include/bits/wordsize.h /usr/include/bits/long-double.h \
 /usr/include/gnu/stubs.h /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h ../threads/system.h \
 ../threads/thread.h ../threads/scheduler.h ../threads/list.h \
 ../machine/interrupt.h ../machine/stats.h ../machine/timer.h \
 ../threads/utility.h
sysdep.o: ../machine/sysdep.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h /usr/include/stdio.h \
 /usr/include/bits/libc-header-start.h /usr/include/features.h \
 /usr/include/sys/cdefs.h /usr/include/bits/wordsize.h \
 /usr/include/bits/long-double.h /usr/include/gnu/stubs.h \
 /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h /usr/include/signal.h \
 /usr/include/bits/sigset.h /usr/include/bits/signum.h \
 /usr/include/bits/types/struct_timespec.h /usr/include/bits/siginfo.h \
 /usr/include/bits/sigaction.h /usr/include/bits/sigcontext.h \
 /usr/include/bits/sigstack.h /usr/include/sys/ucontext.h \
 /usr/include/bits/pthreadtypes.h /usr/include/bits/sigthread.h \
 /usr/include/sys/types.h /usr/include/bits/types/clock_t.h \
 /usr/include/bits/types/clockid_t.h /usr/include/bits/types/time_t.h \
 /usr/include/bits/types/timer_t.h /usr/include/endian.h \
 /usr/include/bits/endian.h /usr/include/bits/byteswap.h \
 /usr/include/bits/byteswap-16.h /usr/include/bits/uintn-identity.h \
 /usr/include/sys/select.h /usr/include/bits/select.h \
 /usr/include/bits/types/struct_timeval.h /usr/include/sys/sysmacros.h \
 /usr/include/bits/sysmacros.h /usr/include/sys/time.h \
 /usr/include/sys/socket.h /usr/include/sys/uio.h /usr/include/bits/uio.h \
 /usr/include/bits/socket.h /usr/include/bits/socket_type.h \
 /usr/include/bits/sockaddr.h /usr/include/asm/socket.h \
 /usr/include/asm-generic/socket.h /usr/include/asm/sockios.h \
 /usr/include/asm-generic/sockios.h \
 /usr/include/bits/types/struct_osockaddr.h /usr/include/sys/file.h \
 /usr/include/fcntl.h /usr/include/bits/fcntl.h \
 /usr/include/bits/fcntl-linux.h /usr/include/linux/falloc.h \
 /usr/include/bits/stat.h /usr/include/sys/un.h /usr/include/sys/mman.h \
 /usr/include/bits/mman.h /usr/include/bits/mman-linux.h \
 /usr/include/unistd.h /usr/include/bits/posix_opt.h \
 /usr/include/bits/environments.h /usr/include/bits/confname.h \
 /usr/include/getopt.h /usr/include/stdlib.h /usr/include/errno.h \
 /usr/include/bits/errno.h /usr/include/linux/errno.h \
 /usr/include/asm/errno.h /usr/include/asm-generic/errno.h \
 /usr/include/asm-generic/errno-base.h ../machine/interrupt.h \
 ../threads/list.h ../threads/copyright.h ../threads/utility.h \
 ../machine/sysdep.h ../threads/system.h ../threads/thread.h \
 ../threads/scheduler.h ../threads/list.h ../machine/interrupt.h \
 ../machine/stats.h ../machine/timer.h ../threads/utility.h
stats.o: ../machine/stats.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../threads/utility.h ../threads/copyright.h \
 ../machine/sysdep.h /usr/include/stdio.h \
 /usr/include/bits/libc-header-start.h /usr/include/features.h \
 /usr/include/sys/cdefs.h /usr/include/bits/wordsize.h \
 /usr/include/bits/long-double.h /usr/include/gnu/stubs.h \
 /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h ../machine/stats.h
timer.o: ../machine/timer.cc /usr/include/stdc-predef.h \
 ../threads/copyright.h ../machine/timer.h ../threads/utility.h \
 ../threads/copyright.h ../machine/sysdep.h /usr/include/stdio.h \
 /usr/include/bits/libc-header-start.h /usr/include/features.h \
 /usr/include/sys/cdefs.h /usr/include/bits/wordsize.h \
 /usr/include/bits/long-double.h /usr/include/gnu/stubs.h \
 /usr/include/gnu/stubs-32.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stddef.h \
 /usr/include/bits/types.h /usr/include/bits/typesizes.h \
 /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
 /usr/lib/gcc/x86_64-pc-linux-gnu/5.4.0/include/stdarg.h \
 /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
 /usr/include/string.h /usr/include/xlocale.h ../threads/system.h \
 ../threads/utility.h ../threads/thread.h ../threads/scheduler.h \
 ../threads/list.h ../machine/interrupt.h ../threads/list.h \
 ../machine/stats.h ../machine/timer.h
# DEPENDENCIES MUST END AT END OF FILE
# IF YOU PUT STUFF HERE IT WILL GO AWAY
# see make depend above
