(For English, see README-en_US.md)

pour compiler :

    # mv ../sutil/lib/libsutil.a /usr/local/lib/
    # ln -s /home/leicht/Programmes/fox/tuxplc/sutil/src /usr/local/include/sutil
    # mv ../tuxeip/lib/libtuxeip.a /usr/local/lib/
    # ln -s /home/leicht/Programmes/fox/tuxplc/tuxeip/src /usr/local/include/tuxeip :

Test :

    cat test/test_read.json | netcat -q 10 localhost 17560

