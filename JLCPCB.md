# JLCPCB-batterychargerunit
Li-ion Charger Unit

DESCRIPTION
This PCB is designed for charge, discharge and monitor operation for Li-ion batteries. It will be used to increase battery efficiency and protect health in electric vehicles. After balancing and reading operations on the card itself, it will transfer data to the different unit of the vehicle.

You can find detailed information about our vehicle and team by visiting hidroana.com web page.

For the Gerber File, Follow and message me on
https://www.linkedin.com/in/onur-surgun/

-----------------------------------------------------------------------------------------------------------------------------

DETAILS
This PCB is designed for charge, discharge and monitor operation for Li-ion batteries. It will be used to increase battery efficiency and protect health in electric vehicles. After balancing and reading operations on the card itself, it will transfer data to the different unit of the vehicle.

Introduction:
For current reading, 2 x 2m Ohm 6 W sense resistors are used. These are amplified with the help of current sense amplifier and displayed on STM32F103C8T6 microcontroller.
Since we have 15 cells, we use the BQ7694006DBT IC. Thanks to this integrated, we do both voltage reading and voltage balancing. On the embedded system, the microcontroller and BQ integrated communicate with the I2C protocol.
As the output of the card, all data is transferred from STM32 via UART connection.

STM32F103C8T6:

•32-bit microcontroller
•64 or 128 Kbytes of Flash memory
•20 Kbytes of SRAM
•12-bit ADC resolution
•72 MHz max clock freq.

BQ76940:

– LiFePO4, Li-Ion, Li-Polymer battery type
– Internal ADC measures cell voltage, die temperature, and external thermistor
– Hardware protection features
– Overcurrent in Discharge (OCD)
– Short Circuit in Discharge (SCD)
– Overvoltage (OV)
– Undervoltage (UV)
– Secondary protector fault detection


-----------------------------------------------------------------------------------------------------------------------------

Order Your JLCPCB
We have the PCB design and it's time to order the PCBs. For that, you just have to go to JLCPCB and click the “Instant Quote” button. JLCPCB is the sponsor of this project. JLCPCB (ShenzhenJLC Electronics Co., Ltd.) is the largest PCB prototype enterprise in China and a high-tech manufacturer specializing in rapid PCB prototype and small batch PCB production.

You can order at least 5 PCBs for just $2. Upload the Gerber file you downloaded in the last step to fabricate the PCB. Upload .rar file or you can also drag and drop Gerber files. After uploading the .rar file, you will see a success message below the successfully uploaded file. You can inspect the PCB in Gerber viewer to make sure everything is ok.

You can view both the top and bottom of the PCB. After making sure our PCB looks good, we can now place the order at a reasonable price. You can order 5 PCBs for just $2. You can see what the individual options are and what they are used for, on JLCPCB's user-friendly website. Of course, the price will vary depending on the PCB board size and the extra services you choose. In order to have it produced in the cheapest and shortest time, I suggest you order according to the options selected as standard.

Click the "SAVE TO CART" button to place an order.

After entering your information, you can order with the desired shipping option.

In addition to PCB production, you can also have SMT-Stencil produced for your board, which will assist you during 3D printing and production. With the help of JLCPCB, it's that simple to get anything produced.

https://jlcpcb.com/HAR


