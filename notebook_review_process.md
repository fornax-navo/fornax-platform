# How Does Fornax Review Notebooks?
***

This is a sort of requirements document for notebooks contributed to Fornax by Fornax team members.  When a notebook is deemed "finished" by its authors, it should go through a two part review; a science review and a tech review.  Suggested checklists for those reviews are below. Checklists have been written and maintained by the distributed Fornax team.

For authors: consider these checklists requirements for your code.

## Who should participate in these reviews?
- JK's suggestion is that if everyone on Fornax helps to write the below checklists, then the whole team does not need to be involved in code reviews.  One developer per tech review, one scientist per science review, from any team.
  


## Science Review Checklist
- Is there a use case in the introduction which motivates the code?  will our community understand this motivation/code?
- Does the code do what the intro says it is going to do?
- Is it scientifically accurate?
- Does it include all three archives HEASARC, MAST, IRSA?\
      - if not, is that justified
- Does it include work linked to a buzzword:
	- big data, spectroscopy, time domain, forced photometry, cloud


## Tech Review Checklist
- Is every function documented?
- Does it follow the style guide? https://github.com/spacetelescope/style-guides/blob/master/guides/jupyter-notebooks.md
- Is everything that gets done more than once turned into a function?
- Are errors handled appropriately?
- Are most lines of code commented?
- Is archival data accessed in the most efficient way according to that archive?
- Is data accessed from the cloud where possible?
- Is the code parallelized where possible?
- If the notebook is intended to be scaled up, does it do that efficiently?
- Is memory usage optimized where possible? 
- Does the code give warnings that need to be followed up?
- Is the requirements.txt file complete and not include un-used libraries?

```python

```