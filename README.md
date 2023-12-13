# Trading History MT4 ReadMe File

This ReadMe file provides a brief overview of the code for the Trading History MT4 program developed by the Forex Robot Easy Team. The program allows users to retrieve historical quotes, create and modify pending orders, open and close immediate orders, and calculate trading volumes based on different methods. 

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Functions](#functions)
5. [Developer's Site and Product Review](#developer-site-and-review)

## Introduction <a name='introduction'></a>

The Trading History MT4 program is designed to assist traders in analyzing their forex trading strategies by providing access to historical quotes and various order management functionalities. The program is written in MQL4 language and can be used within the MetaTrader 4 platform.

## Installation <a name='installation'></a>

To use the Trading History MT4 program, follow these steps:

1. Open the MetaTrader 4 platform.
2. Go to 'File' > 'Open Data Folder' to open the data folder.
3. In the data folder, locate the 'MQL4' folder.
4. Within the 'MQL4' folder, create a new folder named 'TradingHistoryMT4' (or any desired name).
5. Copy the provided code into a new file within the 'TradingHistoryMT4' folder.
6. Save the file with a '.mq4' extension.
7. Restart the MetaTrader 4 platform.
8. The program will now be available for use in the platform.

## Usage <a name='usage'></a>

The Trading History MT4 program can be used by calling the various functions provided in the code. The main entry point of the program is the `OnStart()` function, which executes the following actions:

1. Retrieves historical quotes using the `retrieveHistoricalQuotes()` function.
2. Creates a pending order with specified parameters using the `createPendingOrder()` function.
3. Modifies the parameters of a pending order using the `modifyPendingOrder()` function.
4. Deletes a pending order using the `deletePendingOrder()` function.
5. Opens an immediate order with specified parameters using the `openImmediateOrder()` function.
6. Closes an immediate order using the `closeImmediateOrder()` function.
7. Calculates trading volume using the percentage method and the `calculateVolumePercentage()` function.
8. Calculates trading volume using the lot size method and the `calculateVolumeLotSize()` function.
9. Prints the calculated trading volumes.

Users can customize the program by modifying the function parameters and adding additional code as needed.

## Functions <a name='functions'></a>

The Trading History MT4 program provides the following functions:

1. `retrieveHistoricalQuotes()`: Retrieves historical quotes from the strategy tester and displays them in the panel.
2. `createPendingOrder()`: Creates a pending order with the specified symbol, order type, price, stop loss, and take profit.
3. `modifyPendingOrder()`: Modifies the parameters of the specified pending order with the specified stop loss and take profit values.
4. `deletePendingOrder()`: Deletes the specified pending order.
5. `openImmediateOrder()`: Opens an immediate order with the specified symbol, order type, volume, stop loss, and take profit.
6. `closeImmediateOrder()`: Closes the specified immediate order.
7. `calculateVolumePercentage()`: Calculates the trading volume based on the specified percentage of account balance or equity.
8. `calculateVolumeLotSize()`: Determines the trading volume based on the specified lot size.
9. `OnStart()`: The main entry point of the program, where the above functions are called and executed.

## Developer's Site and Product Review <a name='developer-site-and-review'></a>

This code is provided as a sample and is not the official product developed by Forex Robot Easy Team. This code demonstrates the functionality of the Trading History MT4 program as described on the developer's site, forexroboteasy.com. 

For detailed reviews and trading results of the official Trading History MT4 product, please visit the following link: [Trading History MT4 - Product Review](https://forexroboteasy.com/forex-robot-review/review-trading-history-mt4-an-essential-panel-for-analyzing-forex-trading-strategies/)

Please note that ForexRobotEasy is not the official developer of this product. To find the official developer and obtain the official version of the Trading History MT4 program, please refer to the MQL5 marketplace or the official developer's website.
