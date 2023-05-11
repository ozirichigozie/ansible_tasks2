## 2) Create 3 ubuntu machines and 1 centos machine and in your inventory section create a group and call it “webserver”.

>
> - Create another group and call it centos
>
> - All the ubuntu machines should be under the webserver group 
>
> - And the centos machine should be under the group named centos
>
> - Write a playbook to install apache on the centos machine using the group
>
> - Also write a task to make sure apache is started
>
> - In the same playbook write a task that installs nginx on the ubuntu group
>
> - Also write a task to make sure nginx is started
>
> - Lastly create a parent group in the inventory file and put both the webservers and centos group under it.
>
> - Write another task that helps to update the ubuntu server and centos server using the parent group you created. Also install PHP and run it as a pre-task.
>
> NOTE: when done with this task write a detailed blog on the steps you took 
>
