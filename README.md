# Create Your Own Custom Op Amp Models in LTSPICE
## Intro
Here are four examples of op amp models (schematics and symbols). There's variety of ways to model behaviors, these are simply four possible approaches. Copy and modify them anyway you like. 

Over the years, while solving op amp design issues, I began creating SPICE models where I could vary one parameter (Bandwidth, Slew-Rate, etc.) at a time to help isolate and solve the issue. 

Each model's schematic is shown with input parameters and internal calculations. Expand or tweak the behaviors for your own learning or designs.

For each op amp model you'll find:
| Type          | File          |
| ------------- |:-------------:|
| Model         | OPAMP_x.asc   |
| Symbol        | OPAMP_x.asy   |
| Test Circuit  | Test_Circuit_OPAMP_x.asc|

# Easy-to-Use
- Test Circuit
  - Simply copy the three files to a folder and click on the Test Circuit.

- Your Own Circuit
  - Copy the Model and Symbol to your local folder.
  - Create your own schematic, add OPAMP_x.asc from local folder
  - Right-Click Part and enter X to make custom Parameters visible.


## LTSPICE Models
Learn more with full model descriptions along with a hands-on drive test.

- Op Amp - Level 1: Open-Loop Gain, Bandwidth
www.ecircuitcenter.com/LTSPICE/op_amp_models/op_amp_model1.html

- Op Amp - Level 2:  Add Slew-Rate Max
www.ecircuitcenter.com/LTSPICE/op_amp_models/op_amp_model2.html

- Op Amp - Level 3: Add Voltage / Current Limits, Floating Reference
www.ecircuitcenter.com/LTSPICE/op_amp_models/op_amp_model3.html

- Op Amp - Level 4:  Add 2nd and 3rd Poles
www.ecircuitcenter.com/LTSPICE/op_amp_models/op_amp_model4.html


## Solve 10 Op Amp Design Issues using Custom SPICE Models
> Get experience solving design issues including a quick theory refresh section.
>www.ecircuitcenter.com/LTSPICE/op_amp_series_1.html
  
  
Let me know what you find helpful or any other comments. Thanks!
www.ecircuitcenter.com/contact.htm

Have fun on your next learning / design adventure!

Rick  
eCircuit Center  
https://ecircuitcenter.com/
