# Connecting Friends
This project demonstrates how strongly connected components in a directed graph can be used to model friend groups in social networks. Using Kosaraju’s Algorithm, we identify tightly-knit groups of users (like classmates or colleagues), enabling the system to suggest mutual friends and even common interests such as pages or games.

### Key features include:
  1. Identifying strongly connected components (SCCs) representing social groups.
  2. Finding mutual friends between any two users.
  3. Generating a random friend suggestion from a user's friend list.
  4. Intuitive visualization and user interaction via a Tkinter-based GUI.

This system models realistic social behaviors and can be extended for use in recommendation engines and social graph analysis.

## 1. Home Screen – Application Dashboard

![Screenshot 2025-06-28 152251](https://github.com/user-attachments/assets/5c18f39c-dcdc-49d3-9809-ed18d912bb76)

## 2. Home Screen – Application Dashboard
Upon clicking the "Run" button, the application executes Kosaraju’s Algorithm and displays each strongly connected component (SCC). These components represent user clusters or communities where each member is reachable from every other member, similar to real-world friend groups in a social network.

![Screenshot 2025-06-28 152308](https://github.com/user-attachments/assets/6d3bae69-9db1-4942-9cb7-472a148701fa)

## 3. Random Friend Suggestion & No Mutuals
When a user with no connections is queried, or if two users have no mutual friends (like 6 and 9), the system indicates that no mutual friends or friend data is available. This ensures accurate feedback and improves user experience.

![Screenshot 2025-06-28 152346](https://github.com/user-attachments/assets/25ff2d44-5dad-483b-bbeb-65129e229392)

## 4. Mutual Friends Found
Users can enter two IDs (e.g., 8 and 10) to retrieve mutual friends. In this example, the algorithm detects 7 as a common connection between them. This functionality mirrors core social network features such as mutual friend discovery.

![Screenshot 2025-06-28 152324](https://github.com/user-attachments/assets/dfdc1fb0-11e1-41ed-a047-db1068e3e41f)




