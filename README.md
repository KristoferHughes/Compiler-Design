# Compiler-Design
In order to utilize this compiler, the software tool Apache Ant must be installed. 
Using the command "ant" will build the compiler, at which point will be immediately ready to use with the command 
"java -cp build/classes:lib/java-cup-11b.jar MiniJava -X" followed by the path to the file to be analyzed.
In place of the "-X", the letters A, S, T, and P can be used.
S will scan the file, P will parse the file, A will perform semantic analysis of the file, 
T will return a symbol table for the file, and P will translate the file.
