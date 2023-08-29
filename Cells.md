<div align="center">
  <h1>STDCells</h1>
</div>



# Specs of STDCells

* We used only Inverter and NAND gates in order to do the needed Circuit 


 ![Specs](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/247aafab-3812-4b25-b1d1-0d55b7786324)


* the circuit we are required to design

  ![Circuit Diagram](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/33e54206-315e-49f7-bc5d-abb77c345bd3)


# Inverter 

## Schematic

  ![Inverter Schematic](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/728f9815-5836-4fb7-808b-9b6364c7d854)


## Layout 

 ![Inverter Layout](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/bd2c7fcc-1f42-4f42-ab6f-ce62d89d2132)


 ##  Poly , Diffusion , PolyCut, and Fin Layers only 

  ![Inverter Poly Diff and fins](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/3bfa40ac-7c97-49c4-ba1d-9c09ca1c53af)


## M1 , M2 , Vias and Labels 

![Inverter Vias metals and labels](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/886b12af-3f30-44d5-8aba-fc2895ba88ae)


# NAND Gate 

## Schematic 

![NAND Schematic](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/d9322e7f-98d7-4e1d-b873-f79177b1c347)

## Layout

![NAND Layout](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/6f704431-139f-4751-8657-f77fabe5a7f9)


## Poly, Diffusion , Nwell , PolyCUT and Fin layers 

![NAND Poly Diff and Fins](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/3b8d86f0-d0de-4b40-9fb7-3944d8f01de2)


- Note : Diffusion seems to be cut but it's not its a bug of the tool when you zoom out by large scale

## M1 , M2 , Vias and Labels 

![NAND Metals Labels and Vias](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/c18fff6c-d432-4c4f-a5ad-e05d6a2d9b1f)


# XOR Gate using 4 NAND Gates 

## Schematic 

![XOR Schematic](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/25eecb92-daf1-495f-af73-4c94847414c8)


## Layout 

![XOR Layout](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/1c2673b9-8111-4ab8-ace3-0465bf17ef29)


- Note : Those extra Instances in the layout are dummies I had to add to make the diffusion continous.
  
![XOR Layout 2](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/b9a64269-78ee-470f-8e90-c3d3821600fe)

- Note2 : I did not add Bulk ties in this one but I had to added it later for LVS matched results .

## Nwell , Diffusion , Po , Polycut and fin layers

![XOR Poly Diff and Fins](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/cadb0168-94a0-4648-9f2d-33cfa3478827)


## M1, M2 , M3 and Vias 

![XOR Metals Vias and Labels](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/a9d568ab-4e63-44ee-85c2-13d357b1d5ff)



## DRC Clean XOR 

![XOR DRC Clean](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/268f6580-353a-496a-a0fc-58298ee89ed8)


## LVS Matched XOR

![XOR LVS 1](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/f592d5bf-4a3d-4897-b730-4464e1d6ad7f)


![XOR LVS 2](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/039bed8c-bc6f-4de6-a80d-58c3b1787d41)

# Last Circuit Layout using INV and XOR 

## Schematic 

![Schematic](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/beffc334-42e9-427d-99f7-60a8f5909d3c)



## Layout 

![Floorplan](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/367f2184-db7f-4bed-85cd-0bd64c69f61b)

![Layout](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/dfc6b3ea-cff9-4b3b-aab0-0a9f3c2d27d0)

  - Note : I made 2 VDD Power rails and only 1 VSS ground Rail in the middle where I Shared the Bulk Ties with both NMOS from Upper Inverter and XOR and Lower ones .

## NWELL , Diff , Poly , POCUT and Fin Layers

![DIFF Poly Nwell and fins](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/cb397695-7e60-4650-9cc0-41b68ebc00d3)


# M1 M2 M3 , VIAS and labels 

![Metals labels and vias](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/042e5ac7-3190-42e4-938c-7b38f0c2bf1c)


- Orientation Would be : M2 For Vertical Moves , M3 For horizontal , M1 is base metal of the transistor Horizontal for most non basic wiring of transistor .

  # DRC Clean Circuit 

![DRC Clean](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/61e4c738-6e6f-4a86-b5ea-c859a6026d14)


# Matched LVS Circuit

![LVS1](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/becbaeaf-0e61-44a0-96bd-d208724521ac)


![LVS2](https://github.com/MohamedNabil95/CC_STDCells_Layout/assets/90795738/2672b0ba-9f4b-468a-8d2a-7f423f2e6507)



