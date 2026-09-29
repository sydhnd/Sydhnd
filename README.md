### Edge Compute • Custom Kernels • Low-Latency Java & Systems

Building at the seam where numerical algorithms meet bare metal: bridging high-throughput JVM platforms with native runtimes, rewriting sequential bottlenecks into parallel scans, and eliminating runtime overhead from critical execution paths.

---

#### Low-Latency Java & Native Boundaries
* **JDK Foreign Function & Memory (FFM) Integration** — Eliminating off-heap copy penalties by bridging the JVM directly to bare-metal C++ runtimes and custom GPU kernels using zero-copy memory segments.
* **High-Throughput Streaming & In-Memory Grids** — Architecting low-latency, partitioned event pipelines and high-volume processing with Apache Kafka, LMAX Disruptor, and Apache Ignite.
* **Mechanical Sympathy & Runtime Tuning** — Low-overhead critical paths optimized with SIMD-accelerated serialization, custom JAXB tuning, and JVM profiling via Java Flight Recorder.

#### High-Throughput Inference & Kernel Implementations
* **[parallel-lru](https://github.com/sydhnd/parallel-lru)** — Custom GPU kernels implementing parallel-scan Linear Recurrent Units. Replaces sequential time loops with associative prefix scans to benchmark compiled hardware throughput against Python-bound recurrent loops.
* **[gru-lru-cpp](https://github.com/sydhnd/gru-lru-cpp)** — Zero-dependency C++ inference engine for GRU/LRU models. Bypasses heavy frameworks (no PyTorch, no ONNX, no Python runtime) by streaming raw binary weights directly through hand-vectorized AVX2/AVX-512 routines.

#### Physics-Informed ML & Geometric Modeling
* **[pinns](https://github.com/sydhnd/pinns)** — Physics-Informed Neural Networks in PyTorch enforcing governing physical laws (conservation, drag, harmonic oscillators, heat diffusion) directly inside the loss formulation for forward and inverse boundary problems.
* **[geometric-data-analysis](https://github.com/sydhnd/geometric-data-analysis)** — Empirical studies on manifold topology, density distributions, and clustering dynamics to inform structural graph neural network design.
* **[alevel-gnn-predictor](https://github.com/sydhnd/alevel-gnn-predictor)** — Graph neural network architectures trained on relational taxonomies for structural trend forecasting.

#### OS & Systems Internals
* **[minix3-tux35](https://github.com/sydhnd/minix3-tux35)** — Systems workbench exploring microkernel isolation, IPC primitives, and OS subsystem behavior across MINIX 3 and Linux 3.5.

---
