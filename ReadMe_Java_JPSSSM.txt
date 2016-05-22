The zip file contains all java source and the executable jar package.
It's included the Eclipse-Mars Project too.

Some useful considerations on java component
1- JRE System Library 1.8.0.40
2- To execute from command line --> "C:\java -jar jpsssm.jar 120.0" 

Some details on this java implementation:
0- I've treated this case as a java standalone program, so without any consideration as Web Application or Web Service.
1- First Step is validating input price value. 
2- I've loaded Global Beverage Corporation Exchange on JTable (RegistryGBCEmodel --> Beveragecorpex.java)
3- I've recorded about more or less 1 Milion of trade stock on a Jtable in ten seconds (recTrademodel --> RecordTradeBeverage.java).
4- I've used randomic value,in order to record stock data.
5- I've used "Reflection" to load Stock Symbol Type Data (CommonStock.java,PreferredStock.java)

