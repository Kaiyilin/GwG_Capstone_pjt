
### Ask phase 
- What is the object in this project?
  > Using the data to unlock new growth opportunities for the company.
- Who are the stakeholders?
  > Urška Sršen, Sando Mur and the members of Bellabeat marketing analytics team
- Who can I ask for help when I got problems?
  > Bellabeat marketing analytics team
- What is the business task?
  > How people using their smart devices in real life?
 

### Prepare phase
- Where is your data stored and organised?
  > The data is a public data locate at [FitBit Fitness Tracker Data](https://www.kaggle.com/arashnic/fitbit)
  > which contained the personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. 
  > It's a good database that separate people's behaviour based on different time frame in csv format.

- Sort and filter the data
  > The data is stored in csv file (wide or long?)
  > Obtain summary using pnadas library in python
  > What data you'd like to use(filter) and sort?


### Process phase
- Before you start, things you must know and done
  <ol>
    <li> Tools: Python </li>
    <li> Document the cleaning process <br>
  </ol>
- The goal in this phase
  <ol>
    <li> Check the data for errors. </li>
    <li> Transform the data so you can work with it effectively. </li>
  </ol>

- First we check all the data using python


### Analyse phase

- The goal of this pahse
  <ol>
    <li> Aggregate your data so it’s useful and accessible </li>
    <li> Organize and format your data </li>
    <li> Perform calculations </li>
    <li> Identify trends and relationships </li>
  </ol>

### Share phase
- What I discovered
  <ol>
    <li> Generally, we have 33 unique user in this dataset. Overall 33 users track their daily activity, 24 users track their sleep, 14 users track their heart rate and 8 users track their weights. The daily activity tracker is the most popular and the weight track is the least popular service for the user</li> 
    
    <li> Every user (N=33) have track have their daily activity for least 4 days, 30 users track their daily activity more that 20 days </li>

    <li> Generally users sleep between 6-8 hours burn more calories and are more active than those sleep less than 6 hours and greater than 8 hours. The relationship among calories, activity and sleep are limited by this dataset</li>  
  </ol>

- My opinions
  <ol>  
    <li> Company can focus on the devices that with fuctions like tracking daily sleep and daily activity (Leaf and time), since most of the users enjoyed these 2 functions</li>

    <li> Most of the users may not know how to use their devices or not interested in the functions device provide. Only small amout of user (N=3) use all the 4 features the Fitbit provid. Company may need a tutorial for the usage of devices or encourage customers to use the services company provide.</li>

    <li> It shows clear trend that the users with higher daily activity burns more calories per day, it can encourage users if they want to lose their weights</li>
  </ol>
