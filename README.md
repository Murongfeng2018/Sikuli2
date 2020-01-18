# Sikuli2
A successor of project Sikuli with new designs

This project aims at reimplementing Sikuli(http://sikuli.org) with new designs by leveraging modern technology stack:
1. use GraalVM(https://www.graalvm.org/) as the base runtime for running Python and Java code in Sikuli
2. replace Jython with GraalPython(https://github.com/graalvm/graalpython)
3. replace JNI invocations with OpenCV Python API
4. integrate Deep Learning Framework(PyTorch in current stage)
5. simplify the origin software layers/interfaces of Sikuli
6. make use of hardware acceleration for OpenCV, PyTorch, etc
7. improve the Sikuli IDE ...
