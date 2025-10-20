#  🗂️ Cloud-Storage-bucket

![](./images/c56a722d9b33f5c21e27b86750f81050637de934.png)
---


## 🚀 Steps

### 1️⃣ Create a Free AWS Account

1. Go to [https://aws.amazon.com/free](https://aws.amazon.com/free)
2. Click on **Create a Free Account**
3. Follow the sign-up process (email, password, billing info - no charges for free-tier usage)
4. After verification, sign in to the **AWS Management Console**

![](./images/Screenshot%202025-10-01%20185526.png)

5. Log in as the **Root user** (use the email you signed up with)

![](./images/Screenshot%202025-10-01%20185721.png)


6. You’ll be redirected to the **AWS Dashboard**
7. The dashboard looks like this:

![](./images/Screenshot%202025-10-01%20185838.png)

---

### 2️⃣ Open the S3 Service

1. In the AWS Console, search for **S3**
2. Click on the **S3** service to open it



---

### 3️⃣ Create a New S3 Bucket

1. Click **Create bucket**
2. Enter a **unique bucket name** (e.g., `my-first-s3-bucket-1234`)
3. Choose a region (leave as default or select your nearest region)
4. Leave **all other settings as default**, including permissions
5. Click **Create bucket**

![](./images/Screenshot%202025-10-20%20181939.png)

![](./images/Screenshot%202025-10-20%20182436.png)


---

### 4️⃣ Upload an Image (`earth.jpg`) to the S3 Bucket

1. In your bucket, click **Upload**
2. Click **Add files**, and select the `earth.jpg` image from your computer
3. Click **Upload**

![](./images/Screenshot%202025-10-20%20182819.png)

---

### 5️⃣ Make the Image Public with a Bucket Policy

1. Go to the **Permissions** tab of your bucket
2. Scroll down to **Bucket policy**
3. Paste the following policy to allow public access to just the `earth.jpg` file:

![](./images/Screenshot%202025-10-20%20184131.png)


---
### 6️⃣ Copy the Object URL and Open in Your Browser

1. Go to the **Objects** tab inside your S3 bucket
2. Click on the uploaded file: `earth.jpg`
3. Scroll down to the **Object URL**
4. Click the **Copy URL** button
5. Open a new browser tab and **paste the URL** into the address bar



Example URL format : https://cloudbucket4567.s3.us-east-1.amazonaws.com/earth.jpg

![](./images/Screenshot%202025-10-20%20190010.png)

---

### ✅  Done!

 file is now stored in AWS S3.



