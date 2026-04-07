# Barkod Etiket Bilgileri

## Örnek Etiket

### ![Sample Label](media/SampleEnglish.jpg)

## `1. Etiket Yazı Açıklamaları`
#### `1a. Prog No` : 
This value is taken from the `column 1` of the batch file.
***
#### `1b. Araba No`
This value is taken from `column 11` of the batch file.
***
#### `1c. POZ No`
This value is taken from `column 9` of the batch file.
***
#### `1d. İşlem Bilgisi`
This value is taken from `column 15` of the batch file.
##### `1d. İşlem Açıklamaları`
|Bathc File Value |Label Equivalent |Description          |
|-----------------|-----------------|---------------------|
|0                |iSLEM YOK        |                     |
|1                |SU TAHLiYE       |                     |
|2                |KOL YERi         |                     |
|3                |MENTESE          |                     |
|4                |C.ACILIM         |Double opening       |
|5                |T. A. SOL        |Single opening left  |
|6                |T. A. SAG        |Single opening right |
|7                |C. A. SOL        |Double opening left  |
|8                |C. A. SAG        |Double opening right |
|9                |V. O. LEFT       |                     |
|10               |SAG A.KAPI       |Right opening door   |
|11               |SOL A.KAPI       |Left opening door    |
|12               |VASISTAS         |Top opening          |

***

### `1e. Montaj`
This value is taken from `column 10` of the batch file.
##### `1e. Montaj açıklamaları`
|Bathc File Value |Label Equivalent |Description |
|-----------------|-----------------|------------|
|1                |UST(Y)           |Up part     |
|2                |SAG(X)           |Right part  |
|3                |ALT(Y)           |Bottom part |
|4                |SOL(X)           |Left part   |
***

### `1f. Yer No`
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



## `2. Barkod Yazısı Açıklaması`

**`Sample Barcode:`**  

**K1001PROFILE CODE01289400199400**

|K               |1       |001        |PROFILE CODE |0           |1          |28940                         |0               |19940                                |0               |
|----------------|--------|-----------|-------------|------------|-----------|------------------------------|----------------|-------------------------------------|----------------|
|Digit 1         |Digit 2 |Digit 3..5 |Digit 6..17  |Digit 18    |Digit 19   |Digit 20..24                  |Digit 25        |Digit 26..30                         |Digit 31        |
|Fixed Character |Trolley |Box        |Profile Code |Gasket Info |Color Info |Cut Length (28940 = 2894.0mm) |Fixed Character |Other Side Length (19940 = 1994.0mm) |Fixed Character |

***

### `Conta Bilgisi`
|Value|Description |
|-----|------------|
|0    |Conta Yok   |
|1    |Conta Var   |

***

### `Renk Bilgisi`
|Value|Description   |
|-----|--------------|
|1    |Beyaz         |
|2    |Alt Renkli    |
|3    |Üst Renkli    |
|3    |Alt-Üst Renkl |

***
