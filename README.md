# Security Vulnerabilities Reporting

## Learning goals

Through this group work, you will learn how to read code, identify inefficient programming patterns, report them clearly, and improve code using simple data structures and algorithms. You will also practice collaborative development with GitHub, Codespaces, branches, pull requests, and optional AI support.

## Backgroud 

You are given a tiny program with a text-based user interface, which stores and searches basic information about students. The program works, but it contains many inefficient implementation choices. Your task is to find, report, and possibly fix these inefficiencies. The goal is not advanced optimisation. The goal is to notice when code does unnecessary work.

## Preparatory actions

1. Create a new repository for your team based on this template called "wastefulldatahandling".  See instructions at [GitHub Docs: Creating a repository from a template] (https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
3. Protect the main branch of your repository.  Notice a blue warning message about an unprotected branch and follow a link to the branch protection settings.  Under "Protect matching branches", select "Require a pull request before merging". Optionally, to require approval (by another group member) before a pull request can be merged, you can also select "Require approvals". See more instructions at [GitHub Docs: Managing a branch protection rule] https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule

## Workflow actions

1.  Examine the main code (main.py) carefully and test different usage scenarios.
2.  
3.  For finding issues that are more difficult to spot, search online for information about  "SQL injection" and "Directory Traversal".  
4.  As soon as you find a security flaw, use GitHub to file a Security Vulnerability Report. Use this template as a basis of your vulnability report: [Vulnerability Report Templete by GitHub Security Lab] (https://github.com/github/securitylab/blob/main/docs/report-template.md).  The text-based report does not have mandatory fields, but you should provide as much information as possible.  It is particularly important to provide exact steps to reproduce the vulnerablity (in this case,  tested example code on how an attacker could use it).  There must be a separate report for each vulnerability found.
5. If you still have time, try fixing some of the found security  vulnerabilities (or make other well-reasoned improvements to the code).  Please edit the code with Visual Studio Code and, preferably, also try out GitHup Copilot extension (btw, this can also help spot new security flaws). Please always make your code changes first to a new branch, then send pull request to the main repository and merge the repositories.
6. Make sure that all relevant code changes are merged into the main repository before submitting the assigment for review. See Canvas for instructions on how to submit. 
    

