# I Layer Engine  

<img src="undraw_code_inspection_bdl7.svg" width=400>

At the first stage, Meerkat get information about possible vulnerabilities that can couse or be backdoors.      
Examples of the classic vulnerabilities that can be discovered at the first layer are: 
- Use after free
- XSS
- SQL / noSQL injection
- Stack / Heap Overflow  
- Usage of the depricated functions

  
and much more...  
First layer is **additional** and not required but **strongly** recomended. 
<br>

 

## Interation
If your company / organization already use one of the vulnerability scanners you can connect it to Meerkat as the first layer engine.
Everything what you need to do is choose used solution and pass the API key in the configuration file.   
Then Meerkat take advantage on the results returned by Snyk, SonarQube or other supported vulnerability scanner in the final trust factor calculation.

[snyk logo here] [sonarqube logo here]
[example of the cofiguration file in the carbon]


## Tech stack
![tech_stack](tech_stack.png)


2. Vulnerability engine
1. Meerkat API controller and hypervisor
