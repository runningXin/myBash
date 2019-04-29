# utilities

Repository of my own favirite utilities tools. 



sudo du -ab / —max-depth=3 —exclude=‘/data’ | sort -n -r | head -n 100 | awk '{numfmt --to iec $1 }'| awk '{print $1 "\t" $2 }'

du -ab --max-depth=3 --exclude='/data' / | grep -v "Permission denied" | sort -n -r | head -n 200 |    numfmt --to iec

du -ab --max-depth=3 --exclude='/data' / | grep -v "du: cannot read directory" | sort -n -r | head -n 200 |    numfmt --to iec
