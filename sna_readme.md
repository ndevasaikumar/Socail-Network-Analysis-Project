# Mapping Friendships: Social Network Analysis of Facebook Ego Networks

## 📌 Overview
This project focuses on analyzing the **Facebook Combined Ego Network Dataset** using Social Network Analysis (SNA) techniques. The objective is to understand connectivity patterns, influential users, structural properties, and community behavior within ego networks.

The analysis includes graph construction, preprocessing, centrality computation, visualization, and interpretation of insights.

---

## 📁 Dataset
**Facebook Combined Ego Network Dataset (SNAP)**
- Nodes represent users
- Edges represent friendships
- Contains **4,039 nodes** and **88,234 edges**

This dataset models how friendships cluster around individuals ("ego nodes").

---

## 🧠 Key Concepts
### **Ego Network**
An ego network consists of:
- The central user (**ego**)
- Their direct friends (**alters**)
- The connections among those friends

### **Centrality Measures Used**
- **Degree Centrality** – user popularity
- **Betweenness Centrality** – users acting as bridges
- **Closeness Centrality** – ease of reaching others
- **Eigenvector Centrality** – influence of a user based on neighbors

---

## 🛠️ Technologies Used
- **Python 3.x**
- **NetworkX** for graph processing
- **Matplotlib / PyPlot** for visualization
- **PyVis** for interactive network visualization
- **NumPy / Pandas** for data handling
- **Jupyter Notebook** for experiments

---

## ⚙️ Implementation Steps
1. **Load edge-list dataset** from `facebook_combined.txt`
2. **Construct undirected graph** using NetworkX
3. **Extract Largest Connected Component (LCC)** for meaningful analysis
4. **Compute degree distribution**
5. **Calculate centrality metrics**
6. **Generate plots & interactive visualizations**
7. **Analyze top nodes** based on centrality
8. **Export and interpret results**

---

## 🔄 Workflow
1. Load Dataset → 2. Build Graph → 3. Preprocess → 4. Compute Centralities → 5. Visualize → 6. Interpret Insights → 7. Export Results

(Insert activity diagram here if needed in final PDF)

---

## ⭐ Key Features
- Real-world social graph analysis
- Automatic graph preprocessing
- Degree distribution insights
- Top-k central node identification
- Interactive visualization using PyVis
- Exportable analysis outputs

---

## 📊 Outputs
- Degree histogram
- Centrality ranking table
- Interactive HTML graph
- Visualization of LCC

---

## 🚀 Future Scope
- Community detection using Louvain / Girvan-Newman
- Predictive modeling on user influence
- Graph embeddings using DeepWalk or Node2Vec
- Time-based network evolution studies

---

## 📝 References
- SNAP Datasets — Jure Leskovec
- Networks: An Introduction — M. E. J. Newman
- Social Network Analysis — Wasserman & Faust
- Key research papers on centrality measures

---

## 👤 Author
**N. Devasaikumar**
B.Tech — Jaypee Institute of Information Technology

---

If you want, I can generate a **PDF version**, **activity diagram image**, or a **complete project report (10-15 pages)**.

