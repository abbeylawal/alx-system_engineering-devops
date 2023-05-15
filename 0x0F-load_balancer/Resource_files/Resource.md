# 0x0F. Load balancer

DevOpsSysAdmin

-    By: Sylvain Kalache, co-founder at Holberton School
-    Weight: 1
-    Ongoing second chance project - started Apr 28, 2023 6:00 AM, must end by May 3, 2023 6:00 AM
-    An auto review will be launched at the deadline

#### In a nutshell…

-   **Auto QA review:** 0.0/4 mandatory & 0.0/2 optional
-   **Altogether:**  **0.0%**
    -   Mandatory: 0.0%
    -   Optional: 0.0%
    -   Calculation:  0.0% + (0.0% * 0.0%)  == **0.0%**

### Concepts

_For this project, we expect you to look at these concepts:_

-   [Load balancer](https://intranet.alxswe.com/concepts/46)
-   [Web stack debugging](https://intranet.alxswe.com/concepts/68)

![](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/275/qfdked8.png)

## Background Context

You have been given 2 additional servers:

-   gc-[STUDENT_ID]-web-02-XXXXXXXXXX
-   gc-[STUDENT_ID]-lb-01-XXXXXXXXXX

Let’s improve our web stack so that there is [redundancy](https://intranet.alxswe.com/rltoken/xnAaJdhmAxx7PoH3l6EwDg "redundancy") for our web servers. This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. If one web server fails, we will still have a second one to handle requests.

For this project, you will need to write Bash scripts to automate your work. All scripts must be designed to configure a brand new Ubuntu server to match the task requirements.

## Resources

**Read or watch**:

-   [Introduction to load-balancing and HAproxy](https://intranet.alxswe.com/rltoken/B7f3oz8i3Xvvom_YQZzLnQ "Introduction to load-balancing and HAproxy")
-   [HTTP header](https://intranet.alxswe.com/rltoken/sZ9v3Vq2tgLwN_PWVQketw "HTTP header")
-   [Debian/Ubuntu HAProxy packages](https://intranet.alxswe.com/rltoken/2VRAgtKKR9g6Xfb0xzGiSg "Debian/Ubuntu HAProxy packages")

## Requirements

### General

-   Allowed editors: `vi`, `vim`, `emacs`
-   All your files will be interpreted on Ubuntu 16.04 LTS
-   All your files should end with a new line
-   A `README.md` file, at the root of the folder of the project, is mandatory
-   All your Bash script files must be executable
-   Your Bash script must pass `Shellcheck` (version `0.3.7`) without any error
-   The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`
-   The second line of all your Bash scripts should be a comment explaining what is the script doing

## Your servers

Name

Username

IP

State

183861-web-01

Actions Toggle Dropdown

183861-web-02

Actions Toggle Dropdown

183861-lb-01

Actions Toggle Dropdown