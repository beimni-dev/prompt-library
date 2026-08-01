# Example Input

The operation of the processor is determined by the instructions it executes, referred to as machine instructions or computer instructions.
The collection of different instructions that the processor can execute is referred to as the processor’s instruction set.
Elements of a Machine Instruction
Operation code: Specifies the operation to be performed (e.g., ADD, I/O).
Source operand reference: operands that are inputs for the operation.
Result operand reference: The operation may produce a result.
Next instruction reference: address of the next instruction.
Source and result operands can be in one of four areas: Main or virtual memory, Processor register, immediate and I/O Device
The operation of the processor is determined by the instructions it executes, referred to as machine instructions or computer instructions.
The collection of different instructions that the processor can execute is referred to as the processor’s instruction set.
Elements of a Machine Instruction
Operation code: Specifies the operation to be performed (e.g., ADD, I/O).
Source operand reference: operands that are inputs for the operation.
Result operand reference: The operation may produce a result.
Next instruction reference: address of the next instruction.
Source and result operands can be in one of four areas: Main or virtual memory, Processor register, immediate and I/O Device
Within the computer, each instruction is represented by a sequence of bits.
The instruction is divided into fields
It’s difficult to deal with binary representations of machine instructions.
Common practice: use a symbolic representation of machine instructions. E.g. ADD, SUB, MUL…etc.
Instruction Types
Any program written in a high-level language must be translated into machine language to be executed.
Thus, the set of machine instructions must be sufficient to express any of the instructions from a high-level language.
With this in mind we can categorize instruction types as follows:
Data processing: Arithmetic and logic instructions.
Data storage: Movement of data into or out of register and or memory locations.
Data movement: I/O instructions.
Control: Test and branch instructions.

# Example Output

**Main idea:** A processor works by following a set of instructions (its instruction set), and these instructions have specific parts and types.

- **Parts of an instruction**:
  - Operation code – what to do (e.g., ADD)
  - Source operand – the input
  - Result operand – the output
  - Next instruction – where to go next
- Data can come from memory, a register, be given directly (immediate), or from an I/O device.
- Instructions are stored as bits, but simple names (ADD, SUB, MUL) are used since binary is hard to read.
- **4 instruction types**: math/logic, data movement (storage), I/O (movement), and testing/jumping (control).
