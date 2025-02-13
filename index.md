# Automatic Pill Dispenser

### Disigned By: Nathan Yin on Feb 11 2025

---

## Background

Most existing pill dispensers lack the ability to automatically count pills, requiring users to count pills each time manually. This process can be inconvenient and prone to errors, especially for individuals managing multiple medications or those with disabilities. There is a clear need for a more efficient, user-friendly solution that automates both pill counting and dose reminders.

---

### **Design Concepts:**

I chose to use CAD (Computer-Aided Design) software for the initial designs. This method allows faster and more precise visualization of the components than hand-drawn sketches. I can also test if the concept works on a computer to minimize wasting 3D printing filament.

### **Roller and Funnel Mechanism(V1.0)**

Our initial design is based on a “Roller and Funnel” system. The funnel serves as a storage container for the pills before they are dispensed. The roller, functioning as a conveyor belt, moves the pills from the funnel towards a dispensing mechanism. Pills settle into evenly spaced slots on the roller, which then carries them down into a tunnel.

Inside the tunnel, an infrared (IR) sensor detects the number of pills being dispensed. Once the desired quantity is reached, the sensor signals the roller to stop, ensuring precise dispensing. This design combines simplicity and accuracy, making it ideal for controlled pill distribution.

### CHANGE ME: ADD ADVANTAGES

![Screenshot 2025-02-11 at 22.52.52.png](attachment:51cd10c9-f2c4-4b7b-a6f6-f55130790bb6:Screenshot_2025-02-11_at_22.52.52.png)

While the “Roller and Funnel” design has its advantages, it also presents several significant disadvantages

1.	**Adaptability to Different Pill Sizes and Shapes**

•	Pills of varying sizes and shapes require rollers with customized slot dimensions to ensure only one pill fits per slot. Smaller pills may result in multiple pills being dispensed at once, while larger pills may not fit at all.

•	This necessitates frequent manual adjustments or replacements of the roller, which contradicts our original goal of creating a user-friendly design.

2.	**Complexity and Size**

•	The entire mechanism is bulky and complex, increasing the likelihood of mechanical failures.

•	The larger size not only makes manufacturing more expensive but also reduces convenience for users who may struggle to find space for the device in their homes.

3.	**Dependence on a Stepper Motor**

•	To precisely rotate the roller, the design relies on a stepper motor, which adds complexity to the circuit and raises production costs.

•	This further complicates the design and detracts from its intended simplicity and affordability.

---

## Market Research

Today, we conducted a market research study to better understand user needs and analyze our competitors. The goal was to gather insights into what users prioritize in a pill dispenser, such as features, ease of use, and affordability, while also identifying the strengths and weaknesses of existing solutions. This research will guide us in designing a product that stands out in the market and truly meets user expectations.

This is the link to the form:

 https://forms.office.com/pages/designpagev2.aspx?analysis=false&origin=EmailNotification&subpage=design&id=OjY35I1uCE-7qWwzDXODV6d3dSf6yBRNqeJBz273M01UNEtRRlZXTE9WWElXSk02NzAwWEpRTThBUi4u&tab=0

![Screenshot 2025-02-12 at 10.36.52.png](attachment:5e90eb0e-ecbb-43c3-8bfc-374dc8f74f57:Screenshot_2025-02-12_at_10.36.52.png)

**Survey Distribution Plan**

We decided to first distribute the survey to everyone in the school, reaching approximately 500 people. The participants range in age from 12 to 40+, representing various races and genders. This diverse group will provide a broad spectrum of insights, enhancing the reliability and inclusiveness of the data collected.

To distribute the survey we contacted our school (Cambridge Academy For Science and Technology) reception desk to send e-mails to everyone in the school, instead of sending them one by one, because it is not nice to do it that way and its also really slow

**Survey Distribution Method**

To efficiently distribute the survey, we contacted the reception desk at our school and requested them to send the survey email to everyone in the school. This approach was chosen over sending emails individually, as it is not only more respectful but also significantly faster and more efficient.

## FEB13 2025

Today, we received 22 responses to our survey. We will continue collecting responses until the 28th, covering about a week of school due to the half-term break. Most respondents expressed concerns about PillMate® regarding the following issues:
1.	Potential miscounting of pills by the automatic dispenser.
2.	Child safety, as children might open the dispenser and accidentally ingest the pills.
3.	Users forgetting to update dosage settings after switching medications.

“if the device has an error and miscalculates a dose, especially if the medication has strict doses. Also, the cost of replacing a device and making sure children don't have access to the medication being dispensed if it is dispensed automatically.”

“Issues with different sized pills getting caught in the mechanisms, or if medications are switched. if someone went from 2 pills of one concentration, to 1 pill of double concentration (so still same overall dosage) would the device be easy to adapt to that change? or would it accidentally dispense the double dosage?”

![https://github.com/NathanY12345/NathanY12345.github.io/blob/main/Screenshot%202025-02-13%20at%2012.12.36.png)

Adding to the survey findings: Most respondents have never used a pill dispenser or organizer before. However, a significant number of them take pills regularly, with over 50% taking medication monthly and 30% taking it daily. Remarkably, 96% have never used any kind of pill dispenser or organizer.

<img src="relative/path/in/repository/to/image.svg" width="128"/>

## NOTE: This is not the final data, we will update the data again soon.
