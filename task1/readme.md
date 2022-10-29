Logbook for Task1:

28/10 (Written on 29/10):
  Started very late as I thought we needed vBuddy for all tasks, thats what I get for not keeping up with lectures.
  After re-checking that verilator and the toolchain works, part 1 was very easy to understand and implement.
  
  Parts 2-5 was very frustrating, beyond stupid spelling errors, the main issue was that the headers were still not being found, even if i was in the correct directory
  (I think the correct cd is task 1 but i suck at Ubuntu cmd stuff), I was still able to compile the testbench and correctly crete the vcd file but im stil 
  encountering the same problem with the headers.
  
  Part 6 is yet to be completed. Unsure how to open gtkwave anyway.
  
  Met my lab prtner Troy, he got the vBuddy for us
  
29/10:
  Part 6 is weird, I was under the impression we had installed everything we needed in Lab0 but apparently not? When trying to open gtkwave, nut it returned this error
  **Could not initialize GTK!  Is DISPLAY env var/xhost set?** and spat out a bunch of commands. I think this means i have gtkwave installed but apparently i need a
  server to host it?
  
  After searching, I found i had to run this thing called an X server, which is not native on Windows nor WSL (AHH). I downloaded this X server app called Xming.
  Xming ran with success (YES) and I was correctly able to open gtkwave but that gave rise to another problem
