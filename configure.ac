AC_PREREQ([2.69])
LT_PREREQ([2.4.2])

AC_CONFIG_SRCDIR([sds.h])

AC_INIT([sds], [1.0.0], [])
LT_INIT()

AC_SUBST(LIBTOOL_CURRENT, 0)
AC_SUBST(LIBTOOL_REVISION, 0)
AC_SUBST(LIBTOOL_AGE, 0)

# Checks for programs.
AC_PROG_CC

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h string.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_C_INLINE
AC_TYPE_SIZE_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_REALLOC
AC_CHECK_FUNCS([memmove memset strchr])

AC_CONFIG_FILES([Makefile sds.pc])
AC_OUTPUT
