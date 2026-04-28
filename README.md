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
2.  Look for inefficient or wasteful patterns, such as nested loops and repeated sorting.
3.  Before making changes, observe performance, e.g. by counting loop iterations or using time.perf_counter() function.
4.  As soon as you find an inefficiency, create an Energy Efficiency Report as a GitHub issue.
5. Try fixing as many inefficiencies as you can.  Please always make your code changes first to a new branch, then send a pull request to the main repository and merge the repositories.
6. Make sure that all relevant code changes are merged into the main repository before submitting the assigment for review. See Canvas for instructions on how to submit. 
    

