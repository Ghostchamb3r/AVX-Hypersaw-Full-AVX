# AVX-Hypersaw-Full-AVX
An imlementation of the Hyperbolic Tangent Wave Shaping Oscilator aka Hypersaw with SIMD parallel processing in the form of AVX instructions with hermite interpolation in the tanh lookup table. As much of the code was ported to AVX instructions as possible. Sounds good. 

I've included the source for the project as well as a working .dll that can be used with csoundby dropping it into the plugins64 folder. There is also a test .csd file that can be used to run the plugin with real-time MIDI.

As of this writing the plugin and .dll all work. At the time of development and testing, the custom opcode performed as expected. Subsequent operating system changes may have altered the runtime environment in ways that affect current behavior since SIMD intrinsics can be sensitive to changes in instruction set handling, memory layout and alignment, and driver timing.
