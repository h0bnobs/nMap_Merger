# nMap_Merger
<br>Merge multiple nMap xml files into one XML
<br>If you have xsltproc installed it will output in HTML
<pre>
Usage: nMapMerge.py [-h] [-f FILE] [-d DIR] [-q]
<br>Optional Arguments:
<br>    -h, --help              Show this help message and exit
<br>    -f FILE, --file FILE    Parse FILE
<br>    --d DIR, --dir DIR      Parse all xml in directory
<br>    --q, --quiet            Don't print status messages to stdout
<br>    --o, --output           Give a custom filename
</pre>
## Examples:
<pre>
nMapMerge.py -f nMap_out.xml -o merged.xml
nMapMerge.py -d /root/nMap/
</pre>

