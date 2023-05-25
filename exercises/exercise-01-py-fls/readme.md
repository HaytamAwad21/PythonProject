# Exercise 1: Basic Python 


## Objective: 
Familiarize with the following resources -
* Virtual environments 
* Pip operations 
* Dictionaries/Lists 
* Argument Parsing 
* File input/output 
* Work with files: JSON/ YAML 
* String templates 


### Resources: 
* https://realpython.com/python-json/ 
* https://docs.python.org/3/library/json.html 
* http://zetcode.com/python/yaml/ 
* https://yaml.readthedocs.io/en/latest/example.html 
* https://docs.python.org/3/howto/argparse.html 
* https://realpython.com/command-line-interfaces-python-argparse/ 


#### Repository Link: 
https://github.com/gsdevops/gs_training_plan/tree/main/exercises/exercise-01 


## Exercise Details: 
1. Create a python 3 virtual environment named gs_exercises 
2. Pip install pyyaml, jinja2 
3. Create a template which matches the input JSON file (provided in the repo). Utilize python to take input from a configuration file, the command line interface (CLI), or both, and then populate the template with the values, printing the result to STDOUT. There should be a command line argument which allows the user to instead dump the resulting JSON file to disk/storage instead (i.e. similar to how helm templating works) 
4. If time permits, create a script which can parse the JSON file (no need to loop over all members of the list), and convert it to YAML format, again, with the option to print directly to STDOUT, or disk, but not both. 
