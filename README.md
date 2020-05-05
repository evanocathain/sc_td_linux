<b>SC_TD_LINUX</b>

This code disentangles SCAMP data as recorded by the analogue
filterbanks at Parkes, back in the day. Multi-beam or single-beam
files are separated out and written as "dat" files (not to be confused
with PRESTO dat files!)  and "hdr" files. The contents of these are
probably self-explanatory. One can then subsequently do things like
run SIGPROC's filterbank application on the resultant dat files.

On a LINUX system (only!) this code should work by simplying cloning
this repo and then simply typing "make". 


