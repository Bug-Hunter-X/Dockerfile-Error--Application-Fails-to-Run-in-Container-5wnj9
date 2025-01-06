# Dockerfile Bug and Solution

This repository demonstrates a common error in Dockerfiles and provides a solution.

The bug involves missing dependencies or incorrect execution of the application in the CMD instruction, causing the application to fail inside the container.

The solution uses a specific Ubuntu version to avoid unexpected changes, copies requirements.txt before installing packages, and ensures correct execution of the application.