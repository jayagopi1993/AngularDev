# Rabobank Customer Statement Processor (UI)
Create an Angular app that is capable of importing the attached csv-file and visualize it on the screen.

## Input : 
record.csv file.
```bash
“fname”,”lname”,”issueCount”,”dateOfBirth”
"Theo","Jansen",5,"Jun 02 1998"
"Fiona","de Vries",7,"Nov 12 1950"
"Petra","Boersma",1,"Apr 20 2001"
```

## Expected Output :
* User should be able to upload input file from local computer and see the results on screen.
* User should be able to filter the results based on minimal issue count.

# Steps to run the application
1.	Clone the project Rabobank Angular (Angular project)
```bash
git clone https://github.com/jayagopi1993/AngularDev.git
```
2.	Run npm install comment and run ng serve commend.
3.	Access http://localhost:4200 url
4.	Browse and upload input csv file and output will be displayed in the table
5.	Also,User can able to search/filter data using filter text box. The values will be filtered based on issuecount column.

### Screen Shots:

![Screen Shot](https://github.com/jayagopi1993/Assignment/blob/master/documentation/fileUploadUI.PNG?raw=true)


![Screen Shot](https://github.com/jayagopi1993/Assignment/blob/master/documentation/OutputUI.PNG?raw=true)

*NOTICE* : please run backend webservice http://127.0.0.1:8081/RobobankCSP/rabobank/extractCSV

### Backend Webservice Output:
```bash
[{
        fname : "Theo",
        lname: "Jansen",
        issueCount : "5",
        dateOfBirth : "Jun 02 1998"
    },
    {
        fname : "Fiona",
        lname: "de Vries",
        issueCount : "7",
        dateOfBirth : "Nov 12 1950"
    },
	{
        fname : "Petra",
        lname: "Boersma",
        issueCount : "1",
        dateOfBirth : "Apr 20 2001"
    }]
```


#### Developed by [Gopinath Rm](https://github.com/jayagopi1993)
