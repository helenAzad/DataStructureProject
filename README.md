# DataStructureProject
## Project description:
Pharmacy system:
One of the important and necessary things when taking different drugs is to pay attention to the harmful effects that some drugs may have.
put on top of each other and with iodine before taking different drugs at the same time, their effects on each other, in the face
Existence, studied.
In this project, four different data files, each containing the following information, will be provided to you:

• The first dataset: contains information about the names of drugs and their prices.
• The second dataset: The second file contains the names of existing diseases.
• The third dataset: The third file contains the name of each drug and a list of tuples of the names of effective drugs and the type of harmful effect.
it is them If the medicinal effect is not written on the other medicine, it means it does not have a special effect or it has a positive effect that in
There is no difference between being positive or neutral here.
• The fourth dataset: includes the drug sensitivity of drugs on diseases. (The name of the work does not exist and only in the form of a list of
There are tuples of the name of the drug and the type of effect that is either positive or negative, and in this list there are the names of the drugs that have an effect on
they don't have a disease, there is no

* Names of medicines and diseases used in any of these files are not real and are only for testing purposes.
We plan to design a system that contains information on drugs, diseases, and various drug interventions and the effects of drugs on the disease
examine and display together so that the doctor can make the best decision to prescribe drugs.

## Different parts of the project:
• Designing a suitable data structure for storing and retrieving information
• Correct storage of information in RAM and non-contradiction of the stored information with the input
• Implementation of necessary functions to respond to user needs
• User interface design in Console environment for evaluation  

## Data structure design:
In this project, the goal is not text processing and information extraction. Rather, the goal is to implement a suitable data structure that can
At the same time, it can answer the questions raised at a high speed while using the memory optimally.
It can be said that the most important part of this project is the design of the appropriate structure. Structured data design has a direct impact on
It has the speed of running the program and the memory occupied by the program. You should even try to find a balance between the two factors
Save speed and memory.
Proper storage of information in RAM:
After designing the appropriate data structure, the input information must be properly stored in that data structure. Therefore, any absence
Matching the stored information and the input information will lead to errors in the program.

## Implementation of required functions:
Your program should be able to provide the following capabilities to doctors:
1. There is a possibility of CRD of a drug on test (1) and its effects are applied to tests (3) and (4).
 CRD means the set of Delete, Read, Create operations.
2. The Cascade Delete effect of the drug on the datasets should also be performed. That is, if a drug is removed, it should be
Its effect should be applied on datasets (1), (3) and (4).
3. The possibility of CRD of a disease on the data (2) and the effects of drugs on this particular disease.
Apply to the dataset (4).
4. The Cascade Delete effect of the patient on the data should also be performed. That is, if the patient is removed, he must
Its effect should be applied on datasets (2) and (4).
5. It is possible to search on medicines and diseases.
6. It should be possible to enter the name of a medicine, its effects on diseases and harmful effects.
That drug should be displayed along with the type of effect on other drugs.
7. It should be possible that by introducing a disease, drugs that have a positive effect to improve it
are displayed.
8. When adding a new drug to the drug data set, at your own discretion (random example) a number of drugs
Select the available drugs from the dataset and randomly determine which drugs have harmful effects
(Negative) on the newly added iodine drug and also randomly select some diseases from the data.
Select the existing diseases and in data set number (4) the effect of this drug as a positive or negative effect on
Save randomly on those diseases.
9. At the time of adding a new disease, the number of drugs (from dataset 1) should be chosen randomly.
and assign its positive or negative effect (randomly) to that disease and save it in dataset 4.
10. It should be possible to increase or decrease the price of medicines according to the inflation rate. ) inflation rate to
A manual is entered at the entrance and the medicine section is changed.
