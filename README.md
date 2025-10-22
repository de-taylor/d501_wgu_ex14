# D501 - Exercise 15 (Using Exercise 14)

Not putting a lot of effort into explaining what this is, but it had to be a
public repo to work.

If you want to try it, make sure you're signed in to Weights & Biases on your
commandline using `wandb` `(wandblogin)`, then run the following:

```BASH
mlflow run -v 1.0.0 https://github.com/de-taylor/d501_wgu_ex14 -P hydra_options="main.execute_steps='download,preprocess,check_data,segregate,random_forest,evaluate' main.project_name=remote_execution"
```

Feel free to change the project name to something else if you want.