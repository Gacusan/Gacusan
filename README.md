graph TD
    A[Microprocessor] --> B[Control Unit (CU)]
    A --> C[Arithmetic Logic Unit (ALU)]
    A --> D[Registers]
    A --> E[Memory Interface]
    A --> F[Bus Interface]
    
    B -->|Controls flow of instructions| C
    B -->|Controls flow of instructions| D
    C -->|Processes data| D
    E -->|Handles data transfers| D
    F -->|Connects to external devices| E


