### Wio Tracker L1 vs. SenseCAP Card Tracker T1000-E

## Introduction and limitations

Scope, approach, time limitations, and overall laziness — all of this contributes to the
not-that-scientific level of tests that I would like to present to the community.

However, considering all of this, I've tried my best to measure both devices accurately
and under similar conditions.


## Test setup

Both devices were positioned in the same place behind the window. Strong rain stopped me from doing it properly, so this test will be called "beta" — because it's better than nothing.

From both devices I measured ping to one of the nearby repeaters (~800 meters away, quite good reception, almost direct visibility with some minor obstacles).

All measurements were taken around 10 times. To calculate the final numbers, I excluded the best and worst results and took the average of what was left.

Wio L1 was fitted with a kinda-okay ~19 cm portable antenna from Amazon (10 euro, 2 pieces), SWR 1.5 around 868 MHz.

T1000-E has a built-in antenna.


## Results

### Wio Tracker L1

****5.375 dBm there | 11.28125 dBm here****


### SenseCAP Card Tracker T1000-E

At first the results were not looking great at all. After collecting samples, I got the following numbers:

****2.1 dBm there | 9.6 dBm here****

I expected this — it fits well into what I thought the results should be: a small built-in antenna isn't even remotely close to a proper external antenna. But I had a feeling I was missing something.

Orientation! Both antennas were oriented vertically, but the T1000-E antenna can't be as omni-directional as a proper external one.

So I turned the T1000-E 90 degrees and ran the tests again.

****6.0625 dBm there | 10.25 dBm here****

The observed improvement after rotating the device likely results from changes in radiation pattern interaction with the nearby window surface and multipath reflections.

Here I decided to stop and continue in the next days — take some pictures, collect more samples, and do it properly.

New tests will follow.
