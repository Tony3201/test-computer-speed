#!/bin/bash
START=$(date +%s%N);
     for i in {1..100000}
do

   echo "Welcome $i times" 
   done
   END=$(date +%s%N);
   echo $((END-START)) | awk '{print int($1/10000000) "ms"}'

