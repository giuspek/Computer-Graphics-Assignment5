# CS-C3100 Computer Graphics, Fall 2019
# Lehtinen / Aarnio, Kemppinen, Rehn
#
# Assignment 5: Ray Tracing

Student name: Giuseppe Spallitta
Student number: 785354
Hours spent on requirements (approx.): 15 h
Hours spent on extra credit (approx.): about 6 h

# First, a 10-second poll about this assignment period:

Did you go to exercise sessions? Yes, the last one before deadline

Did you work on the assignment using Aalto computers, your own computers, or both? Own computer

# Which parts of the assignment did you complete? Mark them 'done'.
# You can also mark non-completed parts as 'attempted' if you spent a fair amount of
# effort on them. If you do, explain the work you did in the problems/bugs section
# and leave your 'attempt' code in place (commented out if necessary) so we can see it.

R0 Displaying image coordinates       (0.5p): done
R1 Generating rays & ambient lighting (1.5p): done
R2 Visualizing depth		      (  1p): done
R3 Perspective camera		      (1.5p): done
R4 Phong shading		      (  3p): done
R5 Plane intersection		      (  1p): done
R6 Triangle intersection	      (1.5p): done
R7 Shadows			      (1.5p): done
R8 Mirror reflection		      (1.5p): done
R9 Antialiasing			      (  2p): done

# Did you do any extra credit work?

- Refraction (fully implemented)
- Transform object

# Are there any known problems/bugs remaining in your code?

(Please provide a list of the problems. If possible, describe what you think the cause is, how you have attempted to diagnose or fix the problem, and how you would attempt to diagnose or fix it if you had more time or motivation. This is important: we are more likely to assign partial credit if you help us understand what's going on.)

It is not directly a bug on the code, but when I tried to run the render_all.bat file the code did not worked reporting it did not found the compiled code. As a result, I had to change the lines containing "..\bin\assignment_x64_release" (not working, provided in the original code) with "..\bin\assignment_Win32_Release", returning the correct results. If the code will not work in your laptop, maybe returning those lines into their original content would solve the issue.

# Did you collaborate with anyone in the class?

As previous times, I discussed some points with my classmates, in particular with Francesco De Sio and Zeno Sambugaro. Despite this, I wrote my code indipendently.

# Any other comments you'd like to share about the assignment or the course so far?

(Was the assignment too long? Too hard? Fun or boring? Did you learn something, or was it a total waste of time? Can we do something differently to help you learn? Please be brutally honest; we won't take it personally.)

