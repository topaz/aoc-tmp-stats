Seconds to first 10,000 stars of each part of each puzzle of past AoC events.

The times are aggregated; each datapoint is the average number of seconds (rounded down) for the next-fastest N stars, where N is the top-level key `group_size` (currently 10). So with a `group_size` of 10, data like `[5, 10, 15]` means that the average time for stars 1-10 was 5 seconds, the average time for stars 11-20 was 10 seconds, and the average time for stars 21-30 was 15 seconds.
