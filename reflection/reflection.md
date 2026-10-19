# Reflection on Using Codex

Using Codex for my Ames Housing assignment exceeded my expectations. 
I gave it a specific analytical question about remodeling, home age, and sale prices, and then worked through the assignment in stages. 
Overall, I felt Codex did a phenomenal job. 
Although I needed to make some corrections myself, the finished notebook ran successfully and addressed the question I wanted to investigate.

## Where Codex Struggled

The main issue I encountered was syntax. 
I had to go back into the files and fix syntax here and there, which reminded me that generated code still needs human review. 
Codex also initially reported that Python was unavailable before later locating an Anaconda installation. 
That showed me that a problem with the environment can affect its ability to run code, even when the necessary software is installed. 
As the notebook grew, it also accumulated a duplicate summary table and outdated statements saying that no regression had been performed. 
The final review corrected those issues, but they demonstrated why checking the complete notebook matters after several rounds of additions.

## What Surprised Me

I was extremely surprised by how much Codex could accomplish. 
I did not expect it to create a working notebook, clean the relevant data, produce readable charts, fit the requested regression, and explain the findings so clearly. 
One useful result was the difference between the overall comparison and the comparisons within age groups. 
Remodeled homes had lower average prices overall but higher average prices within each age category. 
Codex helped explain how differences in the ages of the homes could contribute to that pattern. 
It also explained why the regression did not support a higher remodeling price difference at every age, rather than reducing the answer to a simple yes or no.

## How My Prompts Evolved

My prompts did not need to change much. 
I felt I was direct about what I wanted and avoided vague requests. 
I named the variables, specified the tools, and explained when Codex should stop before moving to the next stage. 
The prompts progressed from preparation to exploration, regression, findings, and review, but that reflected the assignment's workflow rather than repeated attempts to correct misunderstandings. 
This experience suggested that clear instructions and manageable steps were enough to keep the work focused.

## What I Would Do Differently

If I repeated the task, I would ask Codex to confirm the Python environment first and run the entire notebook after each major stage. 
That could catch syntax problems and execution issues earlier, before later sections depended on them. 
I would still review the code and explanations myself. 
My biggest takeaway is that Codex was a capable collaborator, while my responsibility was to give clear direction and check that the final work was accurate and understandable.
