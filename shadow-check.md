# Firecracker check

This pull request is the production-path test driver for `checks.vixen.rs`.
Its expected result is one policy-defined Linux x86-64 job dispatched over
Vox/Iroh to Yasuo, run at this exact commit inside a disposable Firecracker
microVM, and folded into the fenced aggregate GitHub Check Run.
