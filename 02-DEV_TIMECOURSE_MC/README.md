script runs Monte Carlo analysis
picks 13 random ML IDs and tests whether the mean of the replicates of each timepoint are greater than 100. 
storable.median is a perl storable object that stores timecourse data

# this should work
`perl hgt_timecourse_mc.pl`

# hgt_dev_expr_vals.tar.gz
expression values in transcripts per million for each time point for each HGT gene. 
