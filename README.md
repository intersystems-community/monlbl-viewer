monlbl-viewer
=============
MONLBL Viewer - a web UI for inspecting Caché Monitor (%MONLBL) results.

It provides a minimal metrics for routines (Line-by-Line statistics: Time, TotalTime, Number of executions)
and summary on routines.

What's working now:
-------------------
- Start, Stop, Pause/Resume Caché Monitor
- Show Summary for all monitored routines
- Show detalized view (Line-by-Line) on selected routine
- Syntax highlighting
- "Drilldown" from Routine/ClassMethod call to INT code

What's not working now:
-----------------------
- "Drilldown" for Object's method calls, routine function's call
- Source code view (.cls)
- Changing NAMESPACE to profiling
