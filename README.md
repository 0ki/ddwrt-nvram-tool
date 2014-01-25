ddwrt-nvram-tool
================
This tools allows converts ddwrt nvram binary files to text for easy readability and comparison

<pre>
Usage example:
./nvram2txt first.bin | sort > first.txt
./nvram2txt second.bin | sort > second.txt
meld first.txt second.txt
</pre>
