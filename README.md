# JuniorDev
My attempt at building a junior developer in 4 hours using [WizardCoder](https://huggingface.co/WizardLM/WizardCoder-15B-V1.0).

Live streamed on [Youtube](https://www.youtube.com/watch?v=LElsbw9iBeE)

# Features
- Writes tests (good at this)
- Bootstrapping (great at this)
	- Writes codebases from scratch using a modified GPT-Engineer's generate prompt
- Bug fixing (pretty good at this, needs greater context windows for large codebases)
	- My implementation so far vectorizes the repo it's given, finds top matches to the bug description and rewrites each addressing the bugs.
- Sizes tickets (not well)
- Gives technical feedback (a little better)

# How to use it
For now check out the [Colab](https://colab.research.google.com/drive/1htnj-haXByzvhsXKFzDSqtJtdyd11OVy?usp=sharing) or download the Jupyter Notebook (clone this repo).
