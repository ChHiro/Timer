# Timer

## CMake$B4XO"(B
-  $B%S%k%I(B
    - `make all`
- $B%F%9%H<B9T(B
    - `make test`

## $B%U%!%$%k$NDI2C(B
1. $B%U%!%$%k(B(.cpp$B$^$?$O(B.h$B%U%!%$%k(B)$B$r:n@.(B
1. CMakeLists.txt $B$N(B`PTimer_SOURCES` $B$K:n@=$7$?%U%!%$%k$rDI2C(B

## $B%F%9%H$NDI2C(B
1. $B%U%!%$%k(B(.cpp)$B%U%!%$%k$r:n@=(B
1. CMakeLists.txt $B$N(B`testfiles` $B$K:n@=$7$?%U%!%$%k$rDI2C(B
1. .cpp $B%U%!%$%k$K$O2<5-$N$b$N(B($B$*$^$8$J$$(B)$B$rDI2C$9$k!#(B
    1. `QObject`$B7Q>5$7$?%/%i%9(B
        1. `Q_OBEJCT` $B%^%/%m$,I,MW(B
    1. `QTEST_APPLESS_MAIN(testclassname)` $B$r%U%!%$%k$N:G8e$"$?$j$KDI2C(B
    1. `#include "filename.moc"` $B$r%U%!%$%k$N:G8e$KDI2C(B

