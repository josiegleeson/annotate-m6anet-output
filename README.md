# Annotate m6A modification sites from m6anet

Annotates transcriptomic modification sites with: transcript biotypes, genomic positions and distances to both the upstream and downstream exon boundary using a GTF file.

Please see test_data_m6anet_mod_sites.csv for how the input should be formatted. The output from multiple m6anet sample runs can be combined, and a sample_id and group_id column added. The script will still run if these columns are not present.
