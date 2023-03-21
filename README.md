# libedit
base code: http://thrysoee.dk/editline/libedit-20170329-3.1.tar.gz

### features: libedit-for-CUBRID
1. Use dynamic binding of libtinfo.so at execution time
     * searching libtinfo.so.10 to libtinfo.so.5 sequentially in the user's library path
     * do not link ncurses, tinfo, term
2. Use VI profile for the keyboard map.
3. Accepts TAB key and display it as it is.
