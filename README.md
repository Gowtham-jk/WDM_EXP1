### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 08-08-2025 
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name string
@attribute age numeric
@attribute id numeric
@attribute door numeric
@data
murthi,55,121,5005
kannan,62,122,2342
kamala,58,123,9765
ajith,71,124,9000

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,fog}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
fog,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
fog,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
<img width="365" height="242" alt="Screenshot 2025-08-08 110229" src="https://github.com/user-attachments/assets/86357cfc-753c-4166-b7e6-49832e6c5fe6" />


<img width="490" height="393" alt="Screenshot 2025-08-08 110654" src="https://github.com/user-attachments/assets/0a1db61e-5511-4e95-beba-de4831feb571" />


### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="691" height="253" alt="Screenshot 2025-08-08 110311" src="https://github.com/user-attachments/assets/dab173ae-42c3-453c-ab62-5b8da6fc3488" />
<img width="577" height="415" alt="Screenshot 2025-08-08 110752" src="https://github.com/user-attachments/assets/81f5d6d0-921f-49cb-9a27-6e90c30a8287" />

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1011" height="247" alt="Screenshot 2025-08-08 110348" src="https://github.com/user-attachments/assets/704e921a-be70-460b-8f8a-68b4e1aca557" />
<img width="828" height="422" alt="Screenshot 2025-08-08 110902" src="https://github.com/user-attachments/assets/757eecd4-d398-41cc-8204-874cb19953f0" />

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
<img width="967" height="475" alt="Screenshot 2025-08-08 110819" src="https://github.com/user-attachments/assets/2afe57e8-727c-4cbb-abb8-ced6d1ccae89" />
<img width="1137" height="243" alt="Screenshot 2025-08-08 110424" src="https://github.com/user-attachments/assets/8e943192-6966-42b5-9328-a8489fe05423" />


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
