# 507 Mechanism Model Project

It can be challenge to visualize and truly reason about systems that include rigid body motion – that is, systems where objects are both rotating and translating, and where the motion of one object causes the rotation and translation of other objects. To help you gain more concrete intuition about the relationships between velocities, accelerations, positions, forces, and energies within rigid body motion, we would like each of you to be equipped with a tangible mechanical system that you have made with your own hands.

*Five Hundred and Seven Mechanical Movements* highlight the most important mechanical movements ranging from simple to complex, the mechanisms include cranks, pulleys, drills, wheels, and screws. The goal of this project is to investigate a mechanism of your choice from the “507 Mechanical Movements” website (http://507movements.com). In Phase I of the project, exploratory work on your mechanism is donw with a low-fidelity prototype. In Phase II of the project, deeper understanding of the mechanism is done by simulating the mechanism on Onshape with the use of Onshape REST APIs. 

### Phase 1 (Exploration): Low-fidelity prototype of mechanism 
- Construct a low-fidelity prototype of a mechanism out of plastic board / cardboard and brads
- Research into its application and what function it carries in the real world
- Form a hypothesis of 2 variables of your choice (linear or angular position, velocity, and acceleration)

Materials required: Cardboard or plastic board, brads

*Example for Mechanism 144:*

![image](https://user-images.githubusercontent.com/76875975/183158231-66c6a1eb-19f8-4f9b-8872-4a41487b299d.png)

### Phase 2 (Investigation): CAD Model of mechanism
- Create a CAD model of the mechanism on Onshape
- Configure desired input, output, and other parameters on a copy of the Python notebook below
- Move the mechanism with transformation matrix
- Plot the desired input and output parameters and compare the results to your initial hypothesis

Materials required: [Onshape](https://cad.onshape.com/), [Google Colab](https://colab.research.google.com/)

*Example for Mechanism 144:*

![image](https://user-images.githubusercontent.com/76875975/183158644-1f640959-950c-4299-bcc7-5e531af8b072.png)

### Python Notebook
The Python notebook contains detailed descriptions and instructions of the project. The notebook was designed in a way that allows both students with no programming experience to interact with the engineering concepts through forms and students who would like to further explore the REST API calls in Onshape. Simply locate and open the document named `mechanical-movement.ipynb` in this repository. Click the badge at the top of the page to "Open in Colab" and make a copy!

#### Set-up
1. Make a copy of [this Colab document](https://colab.research.google.com/drive/18T_F8m774aqGe8MKpHaZ2pp1MzjMrRfA?usp=sharing).
2. Follow the instructions of (section 2 of this guide)[https://github.com/PTC-Education/Onshape-Integration-Guides/blob/main/API_Intro.md#2-generating-your-onshape-api-keys] to create your API keys. Such that you can configure your client to access your Onshape document.
3. Import and Setup Onshape Client on the Colab notebook on the first block. Proceed when you see `Onshape client configured - ready to go!`

#### Testing out components
Follow instructions to make sure you can:
1. Get assembly definition
2. View your assembly
3. Move the input of your mechanism
4. Obtain input and output position parameters

#### Putting it all together
Finally, using all the components and functions, create a plot of your desired input and output parameters!
