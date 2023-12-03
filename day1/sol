#!/bin/sh

sed -i 's/zero/z0o/g' input
sed -i 's/one/o1e/g' input
sed -i 's/two/t2o/g' input
sed -i 's/three/t3e/g' input
sed -i 's/four/f4r/g' input
sed -i 's/five/f5e/g' input
sed -i 's/six/s6x/g' input
sed -i 's/seven/s7n/g' input
sed -i 's/eight/e8t/g' input
sed -i 's/nine/n9e/g' input

sed -i 's/[a-zA-Z]//g' input
sed -i 's/^\([0-9]\)$/\1\1/g' input
sed -i 's/^\([0-9]\).*\([0-9]\)$/\1\2/g' input

awk '{sum+=$1} END {print sum}' input
