Combinational Logic Design and Verification
Overview
This lab provided hands-on experience in designing and verifying fundamental combinational logic modules using VHDL. Throughout the process, the emphasis was not only on correct implementation but also on comprehensive testing, debugging, and validation — skills essential for product test engineering roles in hardware companies like AMD.

Key Highlights Focused on Testing and Verification
Rigorous Verification with Exhaustive Testbenches
Each module, including the 2:1 multiplexer, one’s complementor, and adder, was tested with exhaustive or carefully selected input vectors to ensure correctness in all scenarios.

Testbenches were designed to automatically simulate all possible input combinations for small modules (e.g., 2:1 mux), and representative cases for larger N-bit modules (e.g., 32-bit adder).

Waveform outputs from QuestaSim simulations were carefully examined and annotated to validate module behavior.

Debugging and Collaborative Problem Solving
Encountered design bugs during simulation were systematically documented and shared with lab peers in a dedicated channel, reflecting a collaborative and transparent approach to debugging.

Bug reports included symptoms, root cause hypotheses, and ultimately, the verified solutions, ensuring a knowledge-sharing culture—vital for team-based test engineering environments.

Structural and Dataflow Modeling for Design Robustness
Implemented each module in both structural VHDL, using lower-level gate primitives, and dataflow VHDL, utilizing conditional signal assignments.

This dual implementation approach helped cross-verify functionality and increase confidence in design correctness, mimicking real-world engineering where multiple validation methods improve reliability.

Modular, Reusable Design for Scalable Testing
Used generic parameters and generate statements to create scalable N-bit modules from 1-bit building blocks, facilitating reuse and parameterized testing.

Testbenches were modular, supporting easy extension for different bit widths and configurations, mirroring industry best practices for scalable verification.

Adder-Subtractor Design with Integrated Control
Designed a combined adder-subtractor module controlled by a single control bit, integrating multiple components.

This complex combinational module was tested with diverse test cases covering addition and subtraction, highlighting proficiency in testing edge cases and control logic interaction.
