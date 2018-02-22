# cache

## LRU, LFU
LRU: Least Recently used，时间

LFU: Least Frequently used，频率

## LRFU
LRFU: Least Recently/Frequently used，兼顾时间和频率

LRFU算法中为每个缓存块分配一个CRF(Combined Recency and Frequency)，这个CRF值代表该块在未来被使用的可能。过去的每个引用对该值的贡献由一个权值函数F(x)来衡量。F(x)是一个单调降函数，x代表当前时刻
