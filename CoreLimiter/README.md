## CoreLimiter
A mod to automatically limit your game to a certain amount of CPU cores. This can be used to boost performance on some Ryzen CPUs by limiting the game to a single CCX.
Naturally, limiting the game may reduce maximum possible performance under heavy load, and results are highly dependent on how well the game is multithreaded.

You should experiment with settings in a CPU-heavy world or scene to measure performance on your specific system. For CPUs with less than 8 cores it might be worth it to reduce used core count or allow hyperthreads.

This mod is Windows-only. It likely won't do anything on Intel CPUs, but you're free to experiment with it.

Settings:
* Max Cores (default half the physical cores you have) - the maximum amount of cores that the game may use. 4 is the sweet spot on a 2700X/3700X.
* Use both hyperthreads - will use both hyperthreads on cores if enabled (otherwise just one)
* Use first X cores (instead of last) - will use CPU cores starting from first one instead of last one
* Use specific cores - allows you to specify a comma-separated list of cores (including hyperthreads). Cores are numbered starting from zero, and each hyperthread gets a number, so for a 8-core CPU valid values here would range from 0 to 15. 