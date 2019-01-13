# FS-Region-Assingment
Contents of README:
  1. A brief word description of the problem
  2. A brief description of my code
  
* I do have a full-fledged report documenting my findings for the user.

1.
    My fraternity, Phi Gamma Delta, has its international headquarters (IHQ) in the same city that I attend university. While interning at IHQ I noticed an assignment problem that could be solved using mathmematical modeling and integer programming.
    The fraternity of Phi Gamma Delta has 152 chapters and 13 colonies across the contiguous United States and into Canada. IHQ partitions its chapters and colonies into nine regions and employees nine field men. Each candidate is to be assigned to exactly one region. Each region is to be manned by exactly one candidate. The objective is to maximize the total utility of all nine field men. A 9 indicates a most desired preference, and a 1 indicates a least desired preference.
    
2.
    My program uses a 9x9 utility matrix. The data comes from a survey I conducted on the employed field men. I solved for the given optimal value by modeling the assignment problem in AMPL (A Mathematical Programming Language).
   My program finds all the possible solutions to the assignment problem and then sifts through them to see which ones give the optimal value already determined by AMPL. Each of the solutions that give the optimal value are displayed. A frequency bar chart accompanies each solution so that the user can visualize the frequency of each utility in that solution. This helps the user compare optimal solutions.
