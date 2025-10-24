# Elevate_Day5_Vpc-creation

# ☁️ Cloud Networking – VPC Setup (AWS / GCP)


##  Recommended Free Tools
- **AWS Free Tier** – VPC, Subnets, Route Tables, Internet Gateway, Security Groups  

---

## Step-by-Step Summary (AWS Example)

1. **Login to AWS Console**
   - Open **VPC Dashboard**

2. **Create VPC**

<img width="1493" height="799" alt="image" src="https://github.com/user-attachments/assets/9fd0000c-1102-4201-8d26-aa6171855b2c" />
<img width="1399" height="885" alt="image" src="https://github.com/user-attachments/assets/9849227b-ffc3-43d8-980c-d48968dcfebc" />

3. **Create Subnets**
   - Public Subnet → (Enable public IP)
   - Private Subnet → (Disable public IP)

<img width="1569" height="772" alt="image" src="https://github.com/user-attachments/assets/738be163-a44b-4062-ab07-2b7576c4485e" />
<img width="1685" height="270" alt="image" src="https://github.com/user-attachments/assets/0a10fd46-d986-4ed2-816b-3c596d008f9a" />

4. **Create & Attach Internet Gateway**
   - IGW 
  
Internet Gateway

<img width="1599" height="469" alt="image" src="https://github.com/user-attachments/assets/1c6c0fbf-0759-4261-8879-c5d40a20f003" />

5. **Configure Route Tables**
   - Public Route Table → Add route `0.0.0.0/0 → IGW`
   - Associate with **Public Subnet**
   - Private Route Table → No route to internet

Route Table

<img width="1810" height="556" alt="image" src="https://github.com/user-attachments/assets/e8f5ced4-8ded-4ae4-a83b-7eac0f851e28" />


subnet asssociation (Route Table)

<img width="1903" height="440" alt="image" src="https://github.com/user-attachments/assets/c7b68303-77e5-4230-b8b4-7ec9c8ec92f9" />

Edit Routes

<img width="1755" height="443" alt="image" src="https://github.com/user-attachments/assets/a65fc4ec-726c-4b72-8b50-f2d95ac44936" />


