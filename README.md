# PowerApps-PCF-Control-3D-Pie-Charts
PowerApps PCF Control 

 
 
## Components

3D PieChart & 3D Donut Chart

![3D Pie & Donut Chart](https://github.com/nitins2408/PowerApps-PCF-Control/blob/master/3D_piechart.gif)


 
 
## Control Properties

1. By Default it shall pre poulate with the Default data.

2. You need to set your JsonTable ( having Label,Value & Color columns) to the JsonChart Property.  You can set "CityPopulationsJson" if you are using below example



          `ClearCollect( CityPopulations,
    { label: "London",    color: "#B3B3B3",   value: 8615000 },
    { label: "Berlin",    color: "#118dff",        value: 3562000 },
    { label: "Madrid",    color: "#BBDD8C",          value: 3165000 },
    { label: "Hamburg",   color: "#7FB239",        value: 1760000 },
    { label: "Barcelona", color: "#109618",          value: 1602000 },
    { label: "Munich",    color: "#3860B2",        value: 1494000 }
);
 `

3. It has option to adjust X, Y axis coordinate along with the height , X & Y Axis coordonate for the inner radius. If you set inner radius in beteen 0.3-.0.7 it shall be converted to Donut chart. IF set to 0 it will be Pie Chart
  



## PreRequiste
You Should know how to Import the PCF Custom Control to Canvas Powerapp Appication
 
 

## How to use the 3D Pie chart 
1. Download the Managed or UnManged solution from the repository.
2. Import the Solution to your D365 instance 
3. Add the Code component from Solution to the Canvas Powerapp
4. Change the Properties and Ready to Use



## Author
- Nitin Sapkal
 
