# Project3 - Proposal

Objective:
Analytics on EV and Hybrid cars in US with an objective to determine the following
-	Which are the best selling EV brands in the market?
-	How are sales of EV and Hybrid cars trending?
-	What % of EV chrging stations are public and % private
-	What is the density of these charging stations across US
Rationale
-	By analysing heat map businesses can potentially make commercial decisions of opening charging stations
-	Government can decide on public policies for comparable regions in population to incentivise EV+Hybrid uptake
-	Commercial pointers are made available to businesses in terms of investment decisions by further analysis car models and past trends
Limitations
-	Further studies may be needed to establish correlations between similar regions with varying sales and charging stations density

* Dataset
title={Electric &amp; Alternative Fuel Charging Stations 2023},
* url=https://www.kaggle.com/ds/2375714

title={Electric Vehicle Population},
* url=https://www.kaggle.com/dsv/6687350

Examples of charts:

 ![Which are the best selling EV brands in the market - example](https://github.com/Vkrishm/Project3/assets/114547733/baf4efb5-7747-4367-b1a1-4e27c80bd85f)
-	Which are the best selling EV brands in the market?

![How are sales of EV and Hybrid cars trending - example](https://github.com/Vkrishm/Project3/assets/114547733/0e2454f9-987a-499e-a1b7-8888bf902a24)
-	How are sales of EV and Hybrid cars trending?
  
![What % of EV chrging stations are public and % private - example](https://github.com/Vkrishm/Project3/assets/114547733/dcec724d-b785-4501-af09-7512ccff9ebf)
-	What % of EV chrging stations are public and % private
  
![What is the density of these charging stations across US Rationale - example](https://github.com/Vkrishm/Project3/assets/114547733/d95c36f0-5662-421e-9173-2638461e73dd)
-	What is the density of these charging stations across US

# Project 3 - Readme

Overveiw of project (Data Visualisation):

- Electric and Hybrid vehicle (EV/ HV) usage is on the rise across the world
- This story looks at sales data of EV and HV data across 
- It also maps charging stations across US to see where they are concentrated
- Data analytics and charging station concentration arms commercial and public decision makers to direct resources optimally
- Public policy can then be directed in a certain direction
- Commercial decisions can be made optimally based on current and potential sales opportunities
  
--

- Data was stored and extracted in SQL (project 3 final / SQL) folder
- Data visualisations made using Java(Project 3 final/Java) and Project 3 final/visualisations) and Python(data.ipynb)
- Flask with interactive routes (Project 3 Final/API_Flask)

--

How to use and interact with Project:

- Please follow below steps to run html files (In Project 3 final)
- Due to Cross-Origin Resource Sharing  (CORS), html  files are to be run on local server
- Open a local server in the directory of the html file as below
- Clear your browser cache to ensure you're not seeing cached content
- Go to Windows Settings/ Storage and delete Temporary files
- Type http://localhost:8000 to view Java visualisation

--

- Jupyter notebook named "data.ipynb" contains python script
- Analysed data from dataset folders to make dataframe and then visualisations
- At the very bottom all 3 visualisations have been shown
- Library not used in class called "PyPDF2" is used
  
--

- API Flask has three routes you can access (In Project 3 final folder)

--

-java script visualisations in (Project 3 final/visualisations)


Sources for data:
title={Electric &amp; Alternative Fuel Charging Stations 2023},
* url=https://www.kaggle.com/ds/2375714

title={Electric Vehicle Population},
* url=https://www.kaggle.com/dsv/6687350

