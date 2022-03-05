# smart-checksum-tool
A tool that would calculate a split checksum for a file; every 512 KB or so, it would record the SHA256 hash (or similar algorithm), and be able to "repair" damaged files in place by finding and replacing corrupted chunks of data.
