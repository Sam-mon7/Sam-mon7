# Hi, I'm Sam

I'm a Computer Science student at the University of Edinburgh, interested in systems programming, security and graphics.

## Open-source contributions

- Contributed **6 merged PRs** to [AnyPS5](https://github.com/boykopovar/AnyPS5), a PS5 compatibility layer, each with regression tests.
- Fixed a Windows shader-cache race ([#5552](https://github.com/boykopovar/AnyPS5/pull/5552)), a memory-import boot abort ([#5870](https://github.com/boykopovar/AnyPS5/pull/5870)) and Vulkan pipeline leaks ([#7117](https://github.com/boykopovar/AnyPS5/pull/7117)).
- Fixed stack corruption during Windows asynchronous reads ([#8394](https://github.com/boykopovar/AnyPS5/pull/8394)) and invalid Vulkan usage flags on lazily created sampled views ([#7116](https://github.com/boykopovar/AnyPS5/pull/7116)).
- Added opt-in shader preparation on first use, reducing peak private memory from **17.1 GB to 12.2 GB** in a documented Demon's Souls boot test on Windows ([#5872](https://github.com/boykopovar/AnyPS5/pull/5872)).
