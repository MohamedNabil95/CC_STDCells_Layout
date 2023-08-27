<div align="center">
  <h1>STDCells</h1>
</div>



# Specs of STDCells

* We used only Inverter and NAND gates in order to do the needed Circuit 


 ![image](https://github.com/MohamedNabil95/Issues/assets/90795738/7574f9e0-6769-403d-b738-35df5ef4039d)

* the circuit we are required to design

  ![image](https://github.com/MohamedNabil95/Issues/assets/90795738/b37af437-20e9-4b23-8dd4-6e7f96857d50)

# Inverter 

## Schematic

  ![image](https://github.com/MohamedNabil95/Issues/assets/90795738/d196739a-b3c8-4f92-821f-f3528798c307)

## Layout 

 ![image](https://github.com/MohamedNabil95/Issues/assets/90795738/e4e64c68-288e-49e9-92b6-b53bb296ad0d)

 ##  Poly , Diffusion , PolyCut, and Fin Layers only 

  ![image](https://github.com/MohamedNabil95/Issues/assets/90795738/d4eb11ec-6804-4ed8-89a9-57a91471997b)

## M1 , M2 , Vias and Labels 

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/8539dda4-9598-482e-a98a-bb5e6b9deff2)

# NAND Gate 

## Schematic 

![image](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/889485e9-84c8-451f-a4c8-fc5b0e061330)

## Layout

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/e30da2a2-b62b-4370-b6fc-1fc0f779b386)

## Poly, Diffusion , Nwell , PolyCUT and Fin layers 

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/bcc09d94-a885-4ae3-8b04-e28ab17f580c)

- Note : Diffusion seems to be cut but it's not its a bug of the tool when you zoom out by large scale

## M1 , M2 , Vias and Labels 

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/3fd53cf4-556a-4c1d-b4e9-5e91095843bc)

# XOR Gate using 4 NAND Gates 

## Schematic 

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/8469fe3e-f7bf-44f4-92d2-204493091382)

## Layout 

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/b0766523-29eb-4e35-ae37-d7f26501f9a4)

- Note : Those extra Instances in the layout are dummies I had to add to make the diffusion continous.
  
![image](https://github.com/MohamedNabil95/Issues/assets/90795738/10d2c57d-e69d-48ec-807d-df7860bf239a)


- Note2 : I did not add Bulk ties in this one but I had to added it later for LVS matched results .

## Nwell , Diffusion , Po , Polycut and fin layers

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/06d055fd-7089-4170-b81f-52367e27ce9c)

## M1, M2 , M3 and Vias 

![image](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/1f725b84-8ab3-40a1-a9a1-aea7aa4123e1)

## DRC Clean XOR 

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/ddc32233-31a4-413b-994a-97450e6d2f3a)

## LVS Matched XOR

![image](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/f4b9cca0-060e-4e9e-9344-412916a11ec0)

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/21425368-ac58-4aaa-b1ba-78339ef9cf4c)

# Last Circuit Layout using INV and XOR 

## Schematic 

![image](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/b8bb87f3-c7c6-418d-b31e-18552c6c5357)


## Layout 

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/a6c4dd1e-3a9b-41ac-9431-67573f82555e)

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/dc3090eb-8163-4f8f-b62f-f5cbd3515b7f)

  - Note : I made 2 VDD Power rails and only 1 VSS ground Rail in the middle where I Shared the Bulk Ties with both NMOS from Upper Inverter and XOR and Lower ones .

## NWELL , Diff , Poly , POCUT and Fin Layers

![image](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/261cd0ee-8af6-4fc4-a46f-aae74a2aa032)

# M1 M2 M3 , VIAS and labels 

![image](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/1c2a90b3-ec77-4117-8bbe-c15b762d2bb8)

- Orientation Would be : M2 For Vertical Moves , M3 For horizontal , M1 is base metal of the transistor Horizontal for most non basic wiring of transistor .

  # DRC Clean Circuit 

![image](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/252ac8da-b785-42f4-8af9-b825293932bf)

# Matched LVS Circuit

![image](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/63aefff1-4491-4707-a244-d6864d4051b5)

![image](https://github.com/MohamedNabil95/Issues/assets/90795738/cc9ccef1-af1f-4826-a595-817ac0d1730a)



