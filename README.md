# Pascal for cREXX

A Pascal compiler written in cREXX Level B. It translates Pascal programs into
cREXX assembly (`.rxas`), which `rxas` assembles and `rxvm` runs. (Work in progress.)

    make                  # build build/pascal.rxbin and build/pasrt.rxbin
    ./pasc hello.pas      # compile and run
    make test             # run the test programs in tests/
