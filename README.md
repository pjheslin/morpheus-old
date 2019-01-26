This is an old, out-of-date version of the Morpheus morphological parser for Latin and Greek

The current, up-to-date repository for Morpheus is here: https://github.com/PerseusDL/morpheus

The current version of Morpheus has a bug which has led to a significant regression whereby many Greek words are not parsed at all or are not parsed correctly.  Until that bug is fixed, this old version of Morpheus is provided so that Diogenes can build against it.

The binaries in this version compile cleanly (though with many warnings) on Linux, but not OS X.  Recompiling the Greek stemlib, however, causes cruncher to segfault.  So you can run make in the src directory but not in the stemlibs.  The stemlibs should be platform independent anyway, so that should not matter.
