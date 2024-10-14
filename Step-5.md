## Step 5: Commit & Test

- Commit your changes to your Git repository.
- Create a Pull Request and merge it into the main branch.

![image](https://github.com/user-attachments/assets/64eec96b-1e3a-4b13-a06e-5aa599bf757b)

- Access your ansible-jenkins server and navigate to the ansible-config-artifact directory.
- Run the playbook command.

```
  cd /home/ubuntu/ansible-config-artifact
  ansible-playbook -i inventory/uat.yml playbooks/site.yml
```

![image](https://github.com/user-attachments/assets/5c002000-f7ba-4ae0-a53f-8c8d5e117bcd)

![image](https://github.com/user-attachments/assets/7ee8edf1-c487-44f3-baff-02c49034ced1)
You should be able to see both of your UAT Web servers configured and you can try to reach them from your browser:

UAT-WebServer1
![image](https://github.com/user-attachments/assets/8dbb27d3-9039-4267-a682-9301aa8ee70d)

UAT-WebServer2
![image](https://github.com/user-attachments/assets/a418dbd9-6749-4e8a-b93f-0eed115ff6b0)


Our Ansible architecture now looks like this:

![image](https://github.com/user-attachments/assets/14e81f4a-a1eb-4fd4-8e8e-104fe64faa69)
