# logAnalysis
Collection of scripts for log analysis

1. json line files (jsonl) are files where each line is formatted in json, but the file is not. Cloudflare logs are json line files and are difficult to read as-is. Converting a file to a dataframe makes it much easier to read and analyze.

2. ISAM request logs spread among peers and rotated by size rather than time make it difficult to see a full view of a transaction. 'collecting-ISAM-request-logs' extracts logs from multiple appliances and merges them into one super-log.
