# 100 Days Of Code - Log

### Day 0: November 16, 2019 (Project Planning)

**Today's Progress**: 

“Patients are the most underutilized resource in health care” – Warner Slack, 1933-2018. 

After publicly committing to the #100DaysOfCode challenge (Nov 2019), I've decided to spend the next 3 months building an e-patient IoT application to allow health concerned patients to participate fully in their medical care. 

The aim is to build a wearable device "a Thing (sensor)" that measures vital health signs, such as heart rate, blood pressure, body temperature etc. Each "Thing" will have the ability to connect to the "Internet" for data logging and analysis. Every e-patient will use the "Thing" and connect to the "Internet" to establish a database of "the Internet Of Things" (IoT).

Poll is currently live on Twitter(Nov 16, 2019). Challenge updates:

Daily on twitter/Github  
Weekly: Facebook and Instagram
Monthly: Youtube progress videos

#100DaysOfCode #IoT #4IR #FreeHealthCare #epatient

1. Electrocardiogram (ECG), Electrocardiograms (ECGs) are among the most widely used biosignals, as a diagnostic tool in healthcare environment, providing information of the cardiac electrical cycle [1].
2. Heart Rate (HR), Heart rate (HR) is a standard vital sign and has become a routine measurement in both healthcare and fitness/sport activities [1].
3. Blood Pressure (BP), Blood pressure (BP) is considered the most important cardiopulmonary parameter, indicating the pressure exerted by blood against the arterial wall [1]. 
4. Respiration Rate (RR), Respiration rate (RR) is a fundamental physiologic parameter in patient’s observation. In critical illnesses, this is one of the most sensitive indicators such as in case of distress and potential hypoxia [1].
5. Blood Oxygen Saturation (SpO2), Blood oxygen saturation (SpO2) is an extremely valuable vital parameter and easy to measure using photoplethysmography (PPG) technology and pulse oximetry principles. The PPG method enables to acquire blood vessel variation waveform, and when measured using two wavelengths (normally 660 nm and 905 nm) it is possible to estimate blood oxygen saturation [1].
6. Blood Glucose (BG), Blood glucose (BG) is a worldwide measurement need in diabetic’s subjects. It is not measured in a normal procedure of a clinical environment but is important in diabetic global population [1].
7. Skin Perspiration, Skin perspiration is not a clinical parameter, but a physiological sign used to analyse human reaction to several situations. Life situations can cause neurological reactions from the autonomic nervous system (ANS) stimulating an increase of skin sweating [1].
8. Capnography, Blood oxygen saturation measurement by pulse oximetry is a widely used method to access arterial oxygenation but it is not a good method for human ventilation assessment. Capnography is a non-invasive and cost-effective method to evaluate human ventilation, indicating the carbon monoxide levels present in the respiration cycle, being very useful to avoid clinical problems and ensure patient safety [1].
9. Body Temperature, Body temperature (BT) is the outcome of the balance between heat production and heat loss in the body, being its measurement vital to avoid many elements defunctionalisation due to high temperatures [1].


**Thoughts:** 

**Link to work:** 
[1] https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6111409/


### Day 2: November 16, 2019 (Development Hardware and Software selection)

**Today's Progress**: 

Today, I decided on the hardware and software tools to use for developing my E-patient IoT platform. I selected the NodeMCU E-12 wifi board and microcontroller as my IoT platform of choice. And also went with MicroPython over c/c++ as the programming language. After an hour of trying to figure out how to install the MicroPython firmware on the NodeMCU controller for use on Windows OS, I was able to successfully run a blinky example program using the uPyCraft editor. I’ve linked the website below of the tutorial that I used to successfully load firmware and program a blinky using uPyCraft[2].

**Thoughts:** 

I don’t necessarily have the project planned out in detail yet, but I kind of have an idea of what I want to end up with. I’ve written basic code on Python before using a raspberry pi and also used the ESP-03 wifi module with a Nucleo-F446RE board. However, I have never written a large script on Python and also never used the wifi module to its full capacity, hence I selected the NodeMCU microcontroller and MicroPython programming language. Soon coming is my design layout and code to be hosted on this Github repo. 


**Link to work:** 
 
[2] https://randomnerdtutorials.com/getting-started-micropython-esp32-esp8266/
