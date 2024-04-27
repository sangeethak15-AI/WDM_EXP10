### EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 27.04.2024
### AIM: To create a project for Sentimental Analysis on any Dataset (twitter dataset) a Using Rapidminer
### Description: 
<div align = "justify">

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:
<img width="960" alt="ex10-7" src="https://github.com/Shavedha/WDM_EXP10/assets/93427376/23fd7dbf-7392-479f-b0da-ac3e94820a48">

<img width="960" alt="ex10 -1" src="https://github.com/Shavedha/WDM_EXP10/assets/93427376/799c0729-38aa-47c5-9426-c80c5958f158">


<img width="960" alt="ex10 -3" src="https://github.com/Shavedha/WDM_EXP10/assets/93427376/0f8ac178-0470-44a9-a401-57912add0102">
<img width="960" alt="ex10 -2" src="https://github.com/Shavedha/WDM_EXP10/assets/93427376/51f5115e-4ab0-497b-93a9-657b1dcdb633">



<img width="960" alt="ex10-4" src="https://github.com/Shavedha/WDM_EXP10/assets/93427376/e8459fba-83f5-402a-9be6-803f67158f0d">

<img width="960" alt="ex10-5" src="https://github.com/Shavedha/WDM_EXP10/assets/93427376/224bd717-2ed3-453d-a950-ca10db9f9656">

<img width="960" alt="ex10-6" src="https://github.com/Shavedha/WDM_EXP10/assets/93427376/1f14909f-6432-436d-b898-87e1536cb9bb">
<img width="960" alt="image" src="https://github.com/Shavedha/WDM_EXP10/assets/93427376/ba9cf40a-b441-4f39-9b91-4834e6052e89">


### Result:
Thus sentiment analysis in twitter dataset is done successfully using Rapidminer.
