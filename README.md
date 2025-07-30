# Subnetting_Wan_Link_Updates

# ⬛ Subnetting, WAN Link Updates & DNS Configuration in Action

This lab dives into **Class C subnetting** and **WAN link configuration** to enable seamless router-to-router communication. It also demonstrates how to restore **DNS resolution** by updating domain lookup settings on a Cisco router.

---

## 📍 Overview

In this exercise, we used the subnet `192.168.1.112/30` to connect **Router R1** to the **Internet Router**. The lab simulates a common real-world scenario: misconfigured interfaces preventing neighbor adjacency in **OSPF**. After fixing the subnet alignment, routing was restored, and internet reachability was verified.

---

## 🧾 Lab Highlights

- ✅ **Subnet Used**: `192.168.1.112/30`  
  Assigned to router serial interfaces for WAN communication.

- ✅ **OSPF Neighbor Relationship**  
  Initially down due to mismatched subnets. Recovered once both routers were in sync.

- ✅ **DNS Resolution Configuration**  
  Added DNS features to Router 1 using the following commands:
  ```bash
  ip domain-lookup  
  ip name-server 8.8.8.8
✅ Internet Reachability Test
Verified via ping to public IPs after DNS settings were applied.

📸 Screenshots Included
Subnetting Plan

OSPF Neighbor Status Logs

Interface Configuration on R1 and Internet Router

DNS Command Outputs

Successful Pings and Traceroutes

Gateway of Last Resort Confirmation

💬 Key Takeaways
“Seeing routers negotiate and restore connectivity based on IP and protocol adjustments is a powerful way to learn. Subnetting and DNS aren’t just theory — they shape real network behavior.”

📂 Documentation Access
📝 Full configuration walkthrough and screenshots available here:
🔗 https://www.linkedin.com/posts/activity-7356227493478985728-UXNJ?utm_source=share&utm_medium=member_desktop&rcm=ACoAACymwxoByqlhKmdsE21UETiU_1guDiXo3dQ

📌 Tags
#Networking #CCNA #Subnetting #OSPF #DNS #LabPractice #LearningInPublic #TechJourney
