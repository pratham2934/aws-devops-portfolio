# AWS DevOps Portfolio

Beginner learning portfolio for AWS, Linux, Git/GitHub, Jenkins and Ansible.

> **Learning status:** These are starter examples for study. They have not been deployed or validated in your AWS account. Run them in a test environment and document your own test results before describing either project as completed.

## Projects
- **Jenkins + GitHub + AWS EC2 CI/CD:** `projects/jenkins-ec2-cicd/`
- **Ansible Linux web-server automation:** `projects/ansible-webserver/`
- **Interview notes:** `docs/interview-notes.md`

## Safety
- Never commit AWS access keys, passwords, private SSH keys, `.pem` files or Jenkins secrets.
- Store the EC2 private key in Jenkins Credentials, not in this repository.
- Replace example hosts/users with your own test-server details.
- Review commands before running them; use a disposable test environment.

## Suggested workflow
1. Read each project README.
2. Configure a test EC2 instance and restrict SSH access to the Jenkins/control-node IP.
3. Run the Ansible playbook against your test host.
4. Configure Jenkins credentials and parameters, then run the pipeline.
5. Add screenshots and test results only after performing the steps yourself.
