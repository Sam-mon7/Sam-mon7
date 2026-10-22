# Hi, I'm Sam

I'm a Computer Science student at the University of Edinburgh, interested in systems programming, security and graphics.

## Open-source contributions

Merged contributions to [AnyPS5](https://github.com/boykopovar/AnyPS5), working with C++, Windows APIs and Vulkan:

- **Memory safety — [#8394](https://github.com/boykopovar/AnyPS5/pull/8394):** Fixed stack corruption during Windows asynchronous reads by moving a 64 KiB staging buffer off small guest-thread stacks; added a regression test that reproduces the original stack overflow.
- **Shader memory — [#5872](https://github.com/boykopovar/AnyPS5/pull/5872):** Added opt-in shader preparation on first use, reducing peak private memory from 17.1 GB to 12.2 GB in a documented Demon's Souls boot test on Windows; added tests for deferred preparation and first dispatch.
- **Concurrent file I/O — [#5552](https://github.com/boykopovar/AnyPS5/pull/5552):** Fixed a Windows shader-cache race between readers and atomic file replacement, with a regression test and a concurrent-read stress harness.
- **Graphics resource lifetime — [#7117](https://github.com/boykopovar/AnyPS5/pull/7117):** Preserved cached Vulkan pipelines when a buffer pool is created lazily, preventing leaks and unnecessary rebuilds; added a regression test.
- **Memory imports — [#5870](https://github.com/boykopovar/AnyPS5/pull/5870):** Fixed a boot abort by allowing a held memory-import window to expand to its full allocation while keeping existing references valid; added a lifetime regression test.
- **Vulkan validation — [#7116](https://github.com/boykopovar/AnyPS5/pull/7116):** Corrected usage flags on lazily created sampled sRGB views; added a regression test for view creation, sampled values and reuse.

The linked PRs include reproduction steps, test results and validation details.

[Browse my merged upstream PRs](https://github.com/boykopovar/AnyPS5/pulls?q=is%3Apr+is%3Amerged+author%3ASam-mon7)
