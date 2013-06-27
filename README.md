time-delay_mutual-information
=============================

this source contains a non-optimized, sometimes stupidly parallelized, version of the TDMI calculation for a
non-uniformly sampled population.  the data file is assumed to be a matrix
of the form:
mrn time value

the three different versions of the code are listed below:

single_case_raw --- contains a highly adjustable (and thus somewhat
difficult to use) version of the TDMI calculation.

single_case_clean --- contains non-adjustable, but easy to use, version of
the TDMI calcuation

cluster_code --- contains an example script and the code to run it, for
submitting a stupidly paralllel version of the TDMI calculation to matlab
via a torque queue'd cluster.


