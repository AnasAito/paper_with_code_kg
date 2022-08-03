# Paper With Code knowledge graph (pwc_kg)
##  🚀 How to start :
- Step 1 : Create a folder called data 
- Step 2 : Create 3 folders inside raw,bronze,knowledge_graph
- Step 3 : Download data dumps from [pwc repo](https://github.com/paperswithcode/paperswithcode-data) and store them in raw folder
- Step 4 : Run normalization.ipynb , graph_genration.ipynb 
- Step 5 : Open neo4j and create a database 
- Step 6 : Open neo4j_migration.ipynb ,change creds and run the notebook 
- Step 7 : Your database instance is populated and ready to use. Enjoy!
## 🔮 Future improvements : 
- For now pwc don't store links between mathods and all papers (only papers that first mentioned the method)> but it can be parsed from papers web pages and added to source data.
