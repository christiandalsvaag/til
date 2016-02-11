# Hand rolling takes longer

Today I started development on a new deployment tool called Sparrow. The reason I started creating the tool mostly was because I didn't want to take the time to learn and hone my skills using other tools. Well, partly that and the fact that the tools in question (Centurion and Capistrano) didn't cover my use case 100%.

The problem however is that the complexity instantly exploded. There was so much that I needed. I needed some way of managing configuration. How would I do the configuration files for this tool? Was it going to be structured as a Gem? Did that make sense? How would it be sourced into the project in question? An explosion would be an understatement.

Hours later I was still sitting here mostly reading the code from other projects in order to get an idea of how I should solve the problems I had come up with for myself. But this wasn't really helping me, it was making it worse. The thing is that I was trying to create something that had maturity from the start. At the same time I was sitting here thinking about the implementation of this new tool I was also feeling bad about the code that I also should've been writing: the product it self.

Today I learned that writing something on my own will take a lot longer than just using the tools that are out there even though they might not be perfect for my use case. For now I have made Sparrow a private project and it will be ultra-specific to our usecase. We'll use SSHKit and Rake-tasks and there won't be any fancy features.

Instead of starting out with a perfect tool I will do what software is about; I will iterate.
