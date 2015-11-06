monlbl-viewer
=============
MONLBL Viewer - a web UI for inspecting Caché Monitor (%MONLBL) results.

It provides a minimal metrics for routines (Line-by-Line statistics: Time, TotalTime, Number of executions)
and summary on routines.

# Installation

1. Download and import(compile) GMONLBL.Installer.cls.xml
2. In terminal:
   <pre><code>
   set a("Namespace") = {desired namespace}
   (optional)set a("SourceDir") = {project directory}
   do ##class(GMONLBL.Installer).setup(.a)
</code><pre>
3. If you will not specify SourceDir, it will download sources from GitHub
4. It will also create all necessary namespaces, web apps and mapping

What's working now:
-------------------
- Start, Stop, Pause/Resume, Reset Caché Monitor
- Show Summary for all monitored routines
- Show detalized view (Line-by-Line) on selected routine
- Syntax highlighting
- Namespace changing 
