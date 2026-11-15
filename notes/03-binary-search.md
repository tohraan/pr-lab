# Binary search

Halve the search range each step on sorted data for O(log n). The classic bug is computing mid as (lo + hi) / 2 in fixed-width ints, which can overflow.
