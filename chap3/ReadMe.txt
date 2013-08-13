Test : open.c
	step 1: make                      //compile 
	step 2: ./a.out | tee open.log    //add the result to file open.log
	step 3: make clean                //rm *.out and temp file
