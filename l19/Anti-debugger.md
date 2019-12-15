# Anti-debugger

1. Use API IsDebuggerPresent, Read debug bit in TEB
2. Search OllyDbg process name
3. Search window class or title
4. Using UnhandledExceptionFilter, ZwQueryInformationProcess
5. 