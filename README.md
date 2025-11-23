# Original Source

Refer to [Anthropic's repo](https://github.com/anthropics/skills) for the original and most updated source for this. 

I forked this to keep this separate from ant's progression and keep track of the skills i am building (alongside the ones shared by Anthropic already.)

# How to use?

Just fork this repo. For every skill you like, copy the folder to .claude/skills/ in your repo and it would work. 

You can use this with claude code or claude code on the web directly. This repo has the .claude folder with the skill-creator skill. 

# Skills created 

- rl-training-code
- fastapi-backend (opinionated, modify as per your own taste.). This also has links to docs from LLM providers so if you ever want claude to know how to make the correct llm calls, this is the skill to use. 

- vite-frontend-dev. Again opinionated. Not a production level repo, but more like a skeleton to build upon. I like things this way since its the easiest way for me to understand. 

- research-analysis. For epistemic conversations. Yes, your ai needs a lot of instructions to be able to work like this. 

- dry-debugging: Does not work as well for torch code, but works very well for normal debugging. The idea is to catch errors before compilation. It's comprehensive, so confuses the model. 

- swift-app-builder: Claude is not good at writing swift code by default. This skill enforces the right syntax, right checks, and improves the output by a huge factor. 

# TODO

- Add more skills. 
- Add more features to the skills. 