# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
    Pillow
2. Which CVE is linked to this vulnerability?
    CVE-2023-50447
3. What remediation steps do you suggest?
    Upgrade the Pillow package to version 10.2.0 or higher, which fixes an arbitrary code execution vulnerability caused by unsafe handling of the environment parameter in PIL.ImageMath.eval.
### Vulnerability 2:
1. Which vulnerability are you addressing?
    PyYAML
2. Which CVE is linked to this vulnerability?
    CVE-2019-20477
3. What remediation steps do you suggest? 
    Upgrade the PyYAML library to version 5.2 or higher and replace any calls to yaml.load() with yaml.safe_load() when processing untrusted YAML data.
