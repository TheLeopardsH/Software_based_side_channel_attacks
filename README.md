# Software based Side Channel attacks

•C/C++/assembly are not memory-safe:
     •No bounds checking on array accesses 
     •No validity checks on pointer arithmetic or dereferencing 
•Process-based address space isolation does not isolate code from itself!:
      •Malicious inputs can trigger inappropriate memory accesses 
      •Attackers can use those accesses to: 
            •Steal sensitive data from a process or the kernel 
            •Subvert the process’s control flow 
            •Escalate privilege
