# 🧪 Experiment 3: Deploying Nginx Using Docker

---

## 📌 Objective
To deploy and verify Nginx using:
- Official Docker Image  
- Custom Ubuntu Base Image  
- Custom Alpine Base Image  

---

# 🔹 Part 1: Deploy Nginx Using Official Image

### Step 1: Pull the Official Nginx Image
Download the official Nginx image from Docker Hub.

![Step 1](images/exp3/a.png)
![Step 1](images/exp3/b.png)
![Step 1](images/exp3/c.png)
![Step 1](images/exp3/d.png)

---

### Step 2: Run the Container
Start a container using the downloaded image.
![Step 2](images/exp3/e.png)

---

### Step 3: Verify Deployment
Open the browser and check whether the Nginx welcome page is displayed.

![Step 3](images/exp3/f.png)

---

### Step 4: Check Container Status
Verify that the container is running successfully.

![Step 3](images/exp3/g.png)

---

# 🔹 Part 2: Custom Nginx Using Ubuntu Base Image

### Step 1: Create Dockerfile
Create a Dockerfile using Ubuntu as the base image and install Nginx in it.

![Ubuntu Build](images/exp3/h.png)
![Ubuntu Build](images/exp3/i.png)

---

### Step 2: Build Custom Image
Build a Docker image using the created Dockerfile.

![Ubuntu Build](images/exp3/j.png)

---

### Step 3: Run the Container
Start a container using the custom Ubuntu-based image.

![Ubuntu Build](images/exp3/k.png)

---

### Step 4: Verify Output
Check the Nginx webpage in the browser.

![Ubuntu Build](images/exp3/l.png)

---

# 🔹 Part 3: Custom Nginx Using Alpine Base Image

### Step 1: Create Dockerfile
Create a Dockerfile using Alpine Linux as the base image and install Nginx.

![Alpine Build](images/exp3/m.png)

---

### Step 2: Build Image
Build the Docker image using the Alpine-based Dockerfile.

![Alpine Build](images/exp3/n.png)

---

### Step 3: Run Container
Run a container using the newly created Alpine-based image.

![Alpine Build](images/exp3/o.png)

---

### Step 4: Verify Deployment
Open the browser and verify the Nginx welcome page.

![Alpine Build](images/exp3/p.png)

---

# ✅ Result
Nginx was successfully deployed using:
- Official Docker Image  
- Ubuntu Base Image  
- Alpine Base Image  

All containers were verified through browser testing.

---

# 📚 Conclusion

This experiment demonstrated the deployment of Nginx using different Docker images and base operating systems.

From the comparison, it is observed that:

- The **Ubuntu-based image** has the largest size due to more built-in packages.
- The **Official Nginx image** provides a balance between size and usability.
- The **Alpine-based image** is the smallest and most efficient.

Therefore, Alpine-based images are preferred for lightweight and production environments, while Ubuntu-based images are useful for development and debugging purposes.

---


