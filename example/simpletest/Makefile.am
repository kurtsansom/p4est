
# This file is part of p4est.
# Makefile.am in example/simple_test
# included non-recursively from toplevel directory

if P4EST_ENABLE_BUILD_2D
bin_PROGRAMS += example/simpletest/p4est_simpletest
example_simple_p4est_simpletest_SOURCES = example/simpletest/simpletest2.c

LINT_CSOURCES += $(example_simple_p4est_simpletest_SOURCES)
endif

if P4EST_ENABLE_BUILD_3D
bin_PROGRAMS += example/simpletest/p8est_simpletest
example_simple_p8est_simpletest_SOURCES = example/simpletest/simpletest3.c

LINT_CSOURCES += $(example_simple_p8est_simpletest_SOURCES)
endif
