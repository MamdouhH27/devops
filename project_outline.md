\# DevOps Collaboration Project Summary



● GitHub Repository URL: https://github.com/MamdouhH27/devops.git



● Final Web Server Status: Successfully deployed on the Ubuntu 22.04 LTS Virtual Machine. The Docker container is running on port 80, serving the updated web content from Student B. The page includes professional styling and clearly states it was "Updated by Student B". Verified by accessing http://localhost inside the VM.



● Collaboration Notes: 

&nbsp; - Phase 1 (Student A): Created project structure, initialized Git repo, set up Ubuntu VM, wrote Ansible playbook to automate Docker installation, created initial Dockerfile and placeholder index.html, committed and pushed.

&nbsp; - Phase 2 (Student B): Cloned the repository, updated docker/index.html with new content and professional CSS styling, tested locally, committed and pushed changes.

&nbsp; - Phase 3 (Student A): Pulled Student B's changes, re-ran the full pipeline on the VM (Ansible playbook → Docker build → Docker run), verified the final updated web page displays correctly.



The required Git collaboration cycle (push → pull → verify) was successfully demonstrated.

