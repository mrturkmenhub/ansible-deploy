# ansible-deploy

![Ansible Deployment](https://github.com/mrturkmenhub/ansible-deploy/workflows/CI/badge.svg)

Github actions logs can be viewed from following link: 

[https://github.com/mrturkmenhub/ansible-deploy/runs/1542406112?check_suite_focus=true](https://github.com/mrturkmenhub/ansible-deploy/runs/1542406112?check_suite_focus=true)

This is an example repository to demonstrate how Ansible could be used in CI in order to deliver compiled binary from CI. 

I have put the binary file under [./uploads](./uploads/) however, in normal situations, it works like `Unit Test > Integration Test > Development Deploy (pre-release) > Production`

However, the steps might change project to project, it really depends on structure of the project and needs. 

Blog post regarding to this repository can be found here:  [https://mrturkmen.com/posts/deploy-with-ansible/](https://mrturkmen.com/posts/deploy-with-ansible/)



