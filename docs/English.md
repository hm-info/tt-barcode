# Barcode Label Information

## Sample Label 

### ![Sample Label](media/SampleEnglish.jpg)

## `1. Label Text Descriptions`
#### `1a. Prog No` : 
This value is taken from the `column 1` of the batch file.
***
#### `1b. Car/Trolley No`
This value is taken from `column 11` of the batch file.
***
#### `1c. POZ No`
This value is taken from `column 9` of the batch file.
***
#### `1d. Operation Info`
This value is taken from `column 15` of the batch file.
##### `1d. Operation Descriptions`
|Bathc File Value |Label Equivalent |Description          |
|-----------------|-----------------|---------------------|
|0                |NO OPERAT.       |                     |
|1                |WATER SLOT       |                     |
|2                |HANDLE           |                     |
|3                |HINGE            |                     |
|4                |D. OPENING       |Double opening       |
|5                |S. O. LEFT       |Single opening left  |
|6                |S. O. RIGHT      |Single opening right |
|7                |D. O. LEFT       |Double opening left  |
|8                |D. O. RIGHT      |Double opening right |
|9                |V. O. LEFT       |                     |
|10               |RIGHT O. DOOR    |Right opening door   |
|11               |LEFT O. DOOR     |Left opening door    |
|12               |VASISTAS         |Top opening          |

***

### `1e. Part Assembly Location`
This value is taken from `column 10` of the batch file.
##### `1e. Location Descriptions`
|Bathc File Value |Label Equivalent |Description |
|-----------------|-----------------|------------|
|1                |UP(Y)            |Up part     |
|2                |RGT(X)           |Right part  |
|3                |BOT(Y)           |Bottom part |
|4                |LFT(X)           |Left part   |
***

### `1f. Location / Box No`
This value is taken from `column 12` of the batch file. Box number of Trolley.
***

### `1g. Value / Part Length`
This value is taken from `column 2` of the batch file.  
***

### `1h. Frame`
This value is taken from `column 2` and `column 13` of the batch file.  
These values are data with the source tolerance deducted.
***

### `1i. Profile Code`
This value is taken from `column 3` of the batch file.  
***

### `1j. Vendor / Dealer`
This value is taken from `column 16` of the batch file.  
***

### `1k. Client / Cusotmer / Order No`
This value is taken from `column 8` of the batch file.  
***



## `2. Barcode Text Descriptions`

**`Sample Barcode:`**  

**K1001PROFILE CODE01289400199400**

|K               |1       |001        |PROFILE CODE |0           |1          |28940                         |0               |19940                                |0               |
|----------------|--------|-----------|-------------|------------|-----------|------------------------------|----------------|-------------------------------------|----------------|
|Digit 1         |Digit 2 |Digit 3..5 |Digit 6..17  |Digit 18    |Digit 19   |Digit 20..24                  |Digit 25        |Digit 26..30                         |Digit 31        |
|Fixed Character |Trolley |Box        |Profile Code |Gasket Info |Color Info |Cut Length (28940 = 2894.0mm) |Fixed Character |Other Side Length (19940 = 1994.0mm) |Fixed Character |

***

### `Gasket Info`
|Value|Description           |
|-----|----------------------|
|0    |Profile without gasket|
|1    |Profile with gasket   |

***

### `Color Info`
|Value|Description               |
|-----|--------------------------|
|1    |White profile             |
|2    |Bottom colored profile    |
|3    |Top colored profile       |
|3    |Bottom-Top colored profile|

***
