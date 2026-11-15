# Cache locality

CPUs fetch memory in cache lines, so iterating an array in order is far faster than chasing pointers. Row-major vs column-major traversal can differ by 10x.
