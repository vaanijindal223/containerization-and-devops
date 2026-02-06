# Experiment 1: Comparison of Virtual Machines and Containers

## Student Details
- **Name:** Vaani Jindal  
- **SAP ID:** 500119144  
- **Batch:** 2 CCVT  

---

## Aim
To compare **Virtual Machines** and **Containers** by deploying **Nginx** on a Virtual Machine using **Vagrant** and inside a **Docker container**, and observing their resource utilization.

---



## Part A: Virtual Machine Setup (Windows)

### Step 1: Install VirtualBox

Install VirtualBox on your system to create and manage virtual machines.




---

### Step 2: Install Vagrant

Install Vagrant to manage and configure virtual machines easily.  
Verify that Vagrant is installed properly after installation.

![Screenshot](images/exp%201/a.png)


---

### Step 3: Initialize Vagrant with Ubuntu Box

Initialize Vagrant with an Ubuntu box.  
Start the virtual machine and access it using SSH.
![Screenshot](images/exp%201/b.png)
![Screenshot](images/exp%201/d.png)
![Screenshot](images/exp%201/e.png)


---

### Step 4: Install Nginx inside Virtual Machine

Update the system and install Nginx inside the virtual machine.  
Start the Nginx service after installation.

![Screenshot](images/exp%201/f.png)
![Screenshot](images/exp%201/g.png)
![Screenshot](images/exp%201/i.png)

---

### Step 5: Verify Nginx in Virtual Machine

Check whether the Nginx server is running properly in the virtual machine.

![Screenshot](images/exp%201/j.png)


---

### Stop and Remove Virtual Machine

Stop the running virtual machine and remove it when it is no longer needed.

![Screenshot](images/exp%201/k.png)
![Screenshot](images/exp%201/l.png)



---

### Resource Utilization Observation (Virtual Machine)

Observe the resource usage such as memory, CPU, and system performance inside the virtual machine.






---

## Experiment Setup – Part B: Containers using WSL (Windows)

---

### Step 1: Install WSL

Install Windows Subsystem for Linux (WSL) on your system.

![Screenshot](images/exp%201/m.png)


---

### Step 2: Install Ubuntu on WSL

Install Ubuntu distribution using WSL.

![Screenshot](images/exp%201/n.png)


---

### Step 3: Install Docker Engine inside WSL

Install Docker inside the WSL environment.  
Start the Docker service and configure user permissions.

![Screenshot](images/exp%201/o.png)


---

### Step 4: Run Ubuntu Container with Nginx

Run an Ubuntu container and deploy Nginx inside it.

![Screenshot](images/exp%201/p.png)


---

### Step 5: Verify Nginx in Container

Verify that the Nginx server is working properly inside the container.

![Screenshot](images/exp%201/q.png)


---

### Step 6: Container Observation

Monitor the resource utilization of the running container.

![Screenshot](images/exp%201/r.png)


---

## Comparison: Virtual Machine vs Container

| Feature        | Virtual Machine       | Container            |
|----------------|-----------------------|----------------------|
| Boot Time      | Slow                  | Fast                 |
| Resource Usage | High                  | Low                  |
| Isolation      | Full System           | Process Level        |
| Performance    | Moderate              | High                 |
| Size           | Large                 | Small                |

---

## Conclusion

In this experiment, Virtual Machines and Containers were compared based on their setup, performance, and resource utilization.

Virtual Machines provide complete system isolation but consume more resources.

Containers are lightweight, faster, and efficient for application deployment.

Therefore, containers are more suitable for modern cloud and DevOps environments.

