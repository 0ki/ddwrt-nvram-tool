ddwrt-nvram-tool
================
This tools converts ddwrt nvram binary files to text for easy readability and comparison

<pre>
Usage example:
./nvram2txt first.bin | sort > first.txt
./nvram2txt second.bin | sort > second.txt
meld first.txt second.txt
</pre>

It also allows to convert text files back to ddwrt nvram format after editing

<pre>
Usage example:
./nvram2txt nvram.bin > nvram.txt
nano nvram.txt
./txt2nvram nvram.txt new.bin
</pre>
