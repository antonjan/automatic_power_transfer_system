# automatic_power_transfer_system
This repository will have my Power backup system details.<br>
I wanted a way for my Generator to switch over from city power to my generator and when the city power come back up it must automatekely switch the Generator off and switch back to city power.<br>
The auto transfer switch had a monitor aoutput that was used to detect when the city power supply is upp or down<br>
This monitoring output was used to controle the Generator.<br>
This Transfer switch is avalable from Giga Technology http://www.giga.co.za/ocart/index.php?route=product/product&path=96&product_id=376 <br>
![63A_Transfer_swich_2PST_4.jpg](63A_Transfer_swich_2PST_4.jpg?raw=true "Block diagram")<br>
## My requirement was as follow.<br>
1) When my city power is down I will start the Petrol Generator manuely for now.<br>
2) Then the Automatic transfer switch will switch over to my generator.
3) I the switch over the toggel switch on the surcuite in block diagram and switch of the generator on/off switch.<br>
4) The relay will now hold the on/off switch connection in the on postion until the city power comes back up and the automatic transfer switch switch back to city power<br>
5) Becose the transfer switch switched back to city power the power to the Relay is now disconnected and the Generator stops.<br>
6) This system gives me at least a auto stop and transfer back to city power capability<br>
7) My next step is to build an auto start anc chock configuration for the Generator when City Power gos down.<br>
This block diagram explain how I did this.
Block Digarm of Automatic Power Transfer switch.<br>
![Generator_Auto_stop.png](Generator_Auto_stop.png?raw=true "Block diagram")<br>
