---
search:
    keywords: ['compiler_builtins.h', '__multi3', '__divti3', '__udivti3', '__modti3', '__umodti3', '__lshlti3', '__lshrti3', '__ashlti3', '__ashrti3', '__addtf3', '__subtf3', '__multf3', '__divtf3', '__eqtf2', '__netf2', '__getf2', '__gttf2', '__letf2', '__lttf2', '__cmptf2', '__unordtf2', '__extendsftf2', '__extenddftf2', '__fixtfdi', '__fixtfsi', '__fixunstfdi', '__fixunstfsi', '__trunctfdf2', '__trunctfsf2', '__break_point']
---

# file compiler\_builtins.h

**[Go to the source code of this file.](compiler__builtins_8h_source.md)**
|Type|Name|
|-----|-----|
|void|[**\_\_multi3**](group__compiler__builtins_gaa03897335f1fcc54f469e17c32ae9920.md#gaa03897335f1fcc54f469e17c32ae9920) (\_\_int128 & res, uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Multiply two 128 unsigned bit integers (which are represented as two 64 bit unsigned integers. |
|void|[**\_\_divti3**](group__compiler__builtins_gadbd9c6953240b4ca52292ea687d64839.md#gadbd9c6953240b4ca52292ea687d64839) (\_\_int128 & res, uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Divide two 128 bit integers (which are represented as two 64 bit unsigned integers) |
|void|[**\_\_udivti3**](group__compiler__builtins_gaed86fd6c88a54c19700f51a3f36890d3.md#gaed86fd6c88a54c19700f51a3f36890d3) (unsigned \_\_int128 & res, uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Divide two 128 unsigned bit integers (which are represented as two 64 bit unsigned integers) |
|void|[**\_\_modti3**](group__compiler__builtins_gacf950a5162ebd45ceec1463d352a42dd.md#gacf950a5162ebd45ceec1463d352a42dd) (\_\_int128 & res, uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Perform modular arithmetic on two 128 bit integers (which are represented as two 64 bit unsigned integers) |
|void|[**\_\_umodti3**](group__compiler__builtins_ga25eb2263db624647faf0c395b32f2bdb.md#ga25eb2263db624647faf0c395b32f2bdb) (unsigned \_\_int128 & res, uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Perform modular arithmetic on two 128 unsigned bit integers (which are represented as two 64 bit unsigned integers) |
|void|[**\_\_lshlti3**](group__compiler__builtins_ga19640af2c08e820f5aa09069b1827c9b.md#ga19640af2c08e820f5aa09069b1827c9b) (\_\_int128 & res, uint64\_t lo, uint64\_t hi, uint32\_t shift) <br>Perform logical shift left on a 128 bit integer (which is represented as two 64 bit unsigned integers) |
|void|[**\_\_lshrti3**](group__compiler__builtins_ga7785ea89d0105220b2e52ecf5f315caa.md#ga7785ea89d0105220b2e52ecf5f315caa) (\_\_int128 & res, uint64\_t lo, uint64\_t hi, uint32\_t shift) <br>Perform logical shift right on a 128 bit integer (which is represented as two 64 bit unsigned integers) |
|void|[**\_\_ashlti3**](group__compiler__builtins_ga2d057451f581f4d1cec929cf76f0d610.md#ga2d057451f581f4d1cec929cf76f0d610) (\_\_int128 & res, uint64\_t lo, uint64\_t hi, uint32\_t shift) <br>Perform arithmetic shift left on a 128 bit integer (which is represented as two 64 bit unsigned integers) |
|void|[**\_\_ashrti3**](group__compiler__builtins_ga54e1751b41448b01e519dfeb63733ab8.md#ga54e1751b41448b01e519dfeb63733ab8) (\_\_int128 & res, uint64\_t lo, uint64\_t hi, uint32\_t shift) <br>Perform arithmetic shift right on a 128 bit integer (which is represented as two 64 bit unsigned integers) |
|void|[**\_\_addtf3**](group__compiler__builtins_ga873d982bbd7493a9975dd88e923d85ed.md#ga873d982bbd7493a9975dd88e923d85ed) (long double & ret, uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Add two long doubles (which are represented as two 64 bit unsigned integers) |
|void|[**\_\_subtf3**](group__compiler__builtins_ga6f055bf1366a170f3f01b28cc0a723dc.md#ga6f055bf1366a170f3f01b28cc0a723dc) (long double & ret, uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Subtract two long doubles (which are represented as two 64 bit unsigned integers) |
|void|[**\_\_multf3**](group__compiler__builtins_ga74a992741c2e037447d9953bb5cce333.md#ga74a992741c2e037447d9953bb5cce333) (long double & ret, uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Multiply two long doubles (which are represented as two 64 bit unsigned integers) |
|void|[**\_\_divtf3**](group__compiler__builtins_gad8133b5d6604ce3bab0adf8e0d44bf5f.md#gad8133b5d6604ce3bab0adf8e0d44bf5f) (long double & ret, uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Divide two long doubles (which are represented as two 64 bit unsigned integers) |
|int|[**\_\_eqtf2**](group__compiler__builtins_ga11b0c275233be847ecba192c3d4bd50f.md#ga11b0c275233be847ecba192c3d4bd50f) (uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Check equality between two doubles (which are represented as two 64 bit unsigned integers) |
|int|[**\_\_netf2**](group__compiler__builtins_ga01fedff23a9e5324dab56c77a4ce90fa.md#ga01fedff23a9e5324dab56c77a4ce90fa) (uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Check inequality between two doubles (which are represented as two 64 bit unsigned integers) |
|int|[**\_\_getf2**](group__compiler__builtins_gaa4067976976ddf6189ff05068f071421.md#gaa4067976976ddf6189ff05068f071421) (uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Check if the first double is greater or equal to the second double, (the doubles are represented as two 64 bit unsigned integers) |
|int|[**\_\_gttf2**](group__compiler__builtins_ga22ea3ec1bb3c252037a6d1de080f59ec.md#ga22ea3ec1bb3c252037a6d1de080f59ec) (uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Check if the first double is greater than the second double, (the doubles are represented as two 64 bit unsigned integers) |
|int|[**\_\_letf2**](group__compiler__builtins_ga1c52620ce5caeab3f24d20848de48020.md#ga1c52620ce5caeab3f24d20848de48020) (uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Check if the first double is less or equal to the second double, (the doubles are represented as two 64 bit unsigned integers) |
|int|[**\_\_lttf2**](group__compiler__builtins_ga31e5201b17ecf49bf0544d619b3a211e.md#ga31e5201b17ecf49bf0544d619b3a211e) (uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Check if the first double is less than the second double, (the doubles are represented as two 64 bit unsigned integers) |
|int|[**\_\_cmptf2**](group__compiler__builtins_ga130b5f6598f3db086bc0767c6be028c0.md#ga130b5f6598f3db086bc0767c6be028c0) (uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Compare two doubles (the doubles are represented as two 64 bit unsigned integers) |
|int|[**\_\_unordtf2**](group__compiler__builtins_ga26cb1a82545578282008ab4dc67cf262.md#ga26cb1a82545578282008ab4dc67cf262) (uint64\_t la, uint64\_t ha, uint64\_t lb, uint64\_t hb) <br>Check if either of the doubles is NaN, (the doubles are represented as two 64 bit unsigned integers) |
|void|[**\_\_extendsftf2**](group__compiler__builtins_ga3feafc107fc44ac8039a667ee49bcdbf.md#ga3feafc107fc44ac8039a667ee49bcdbf) (long double & ret, float f) <br>Extend float to long double. |
|void|[**\_\_extenddftf2**](group__compiler__builtins_gae76415cbe79dbac141141a706158552c.md#gae76415cbe79dbac141141a706158552c) (long double & ret, double f) <br>Extend float to long double. |
|int64\_t|[**\_\_fixtfdi**](group__compiler__builtins_gafb30709e77efa4ef9eb3bf4d42004ecf.md#gafb30709e77efa4ef9eb3bf4d42004ecf) (uint64\_t l, uint64\_t h) <br>Convert long double (which are split as two 64 bit unsigned integers) into 64 bit integer. |
|int32\_t|[**\_\_fixtfsi**](group__compiler__builtins_gac2669376b81a47fc865f5ba54aea0720.md#gac2669376b81a47fc865f5ba54aea0720) (uint64\_t l, uint64\_t h) <br>Convert long double (which are split as two 64 bit unsigned integers) into 32 bit integer. |
|uint64\_t|[**\_\_fixunstfdi**](group__compiler__builtins_ga459b47b617b89052f544025349c165f8.md#ga459b47b617b89052f544025349c165f8) (uint64\_t l, uint64\_t h) <br>Convert long double (which are split as two 64 bit unsigned integers) into 64 bit unsigned integer. |
|uint32\_t|[**\_\_fixunstfsi**](group__compiler__builtins_ga1c62ec774bd084b04118fdb2b019a5c3.md#ga1c62ec774bd084b04118fdb2b019a5c3) (uint64\_t l, uint64\_t h) <br>Convert long double (which are split as two 64 bit unsigned integers) into 32 bit unsigned integer. |
|double|[**\_\_trunctfdf2**](group__compiler__builtins_ga386f6c017043419d3d33f9e96cc4ae4c.md#ga386f6c017043419d3d33f9e96cc4ae4c) (uint64\_t l, uint64\_t h) <br>Convert long double (which are split as two 64 bit unsigned integers) into double. |
|float|[**\_\_trunctfsf2**](group__compiler__builtins_ga0de0b2a5fe12abf258f7640987807a3a.md#ga0de0b2a5fe12abf258f7640987807a3a) (uint64\_t l, uint64\_t h) <br>Convert long double (which are split as two 64 bit unsigned integers) into float. |
|void|[**\_\_break\_point**](group__compiler__builtins_ga612b3f8baa213fa0ce573eec10bbad78.md#ga612b3f8baa213fa0ce573eec10bbad78) () |


## Detailed Description



**Copyright**

defined in eos/LICENSE.txt 



## Functions Documentation

### function <a id="gaa03897335f1fcc54f469e17c32ae9920" href="#gaa03897335f1fcc54f469e17c32ae9920">\_\_multi3</a>

```cpp
void compiler_builtins.h::__multi3 (
    __int128 & res,
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Multiply two 128 unsigned bit integers (which are represented as two 64 bit unsigned integers. 

Multiply two 128 bit integers split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Post**

`res` is replaced with the result of multiplication Example: 
```cpp
__int128 res = 0;
__int128 a = 100;
__int128 b = 100;
__multi3(res, a, (a >> 64), b, (b >> 64));
printi128(&res); // Output: 10000
```

 




### function <a id="gadbd9c6953240b4ca52292ea687d64839" href="#gadbd9c6953240b4ca52292ea687d64839">\_\_divti3</a>

```cpp
void compiler_builtins.h::__divti3 (
    __int128 & res,
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Divide two 128 bit integers (which are represented as two 64 bit unsigned integers) 

Divide two 128 bit integers split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Post**

`res` is replaced with the result of division Example: 
```cpp
__int128 res = 0;
__int128 a = 100;
__int128 b = 100;
__divti3(res, a, (a >> 64), b, (b >> 64));
printi128(&res); // Output: 1
```

 




### function <a id="gaed86fd6c88a54c19700f51a3f36890d3" href="#gaed86fd6c88a54c19700f51a3f36890d3">\_\_udivti3</a>

```cpp
void compiler_builtins.h::__udivti3 (
    unsigned __int128 & res,
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Divide two 128 unsigned bit integers (which are represented as two 64 bit unsigned integers) 

Divide two 128 bit unsigned integers split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. Example: 
```cpp
unsigned __int128 res = 0;
unsigned __int128 a = 100;
unsigned __int128 b = 100;
__udivti3(res, a, (a >> 64), b, (b >> 64));
printi128(&res); // Output: 1
```

 



### function <a id="gacf950a5162ebd45ceec1463d352a42dd" href="#gacf950a5162ebd45ceec1463d352a42dd">\_\_modti3</a>

```cpp
void compiler_builtins.h::__modti3 (
    __int128 & res,
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Perform modular arithmetic on two 128 bit integers (which are represented as two 64 bit unsigned integers) 

Perform modular arithmetic on two 128 bit integers split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Post**

`res` is replaced with the result of modulus Example: 
```cpp
__int128 res = 0;
__int128 a = 100;
__int128 b = 3;
__modti3(res, a, (a >> 64), b, (b >> 64));
printi128(&res); // Output: 1
```

 




### function <a id="ga25eb2263db624647faf0c395b32f2bdb" href="#ga25eb2263db624647faf0c395b32f2bdb">\_\_umodti3</a>

```cpp
void compiler_builtins.h::__umodti3 (
    unsigned __int128 & res,
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Perform modular arithmetic on two 128 unsigned bit integers (which are represented as two 64 bit unsigned integers) 

Perform modular arithmetic on two 128 unsigned bit integers split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Post**

`res` is replaced with the result of modulus Example: 
```cpp
unsigned __int128 res = 0;
unsigned __int128 a = 100;
unsigned __int128 b = 3;
__umodti3(res, a, (a >> 64), b, (b >> 64));
printi128(&res); // Output: 1
```

 




### function <a id="ga19640af2c08e820f5aa09069b1827c9b" href="#ga19640af2c08e820f5aa09069b1827c9b">\_\_lshlti3</a>

```cpp
void compiler_builtins.h::__lshlti3 (
    __int128 & res,
    uint64_t lo,
    uint64_t hi,
    uint32_t shift
)
```

Perform logical shift left on a 128 bit integer (which is represented as two 64 bit unsigned integers) 

Perform logical shift left on a 128 bit integer split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **lo** Low 64 bits of the 128 bit factor. 
* **hi** High 64 bits of the 128 bit factor. 
* **shift** Number of bits to shift. 



**Post**

`res` is replaced with the result of the operation Example: 
```cpp
__int128 res = 0;
__int128 a = 8;
__lshlti3(res, a, (a >> 64), 1);
printi128(&res); // Output: 16
```

 




### function <a id="ga7785ea89d0105220b2e52ecf5f315caa" href="#ga7785ea89d0105220b2e52ecf5f315caa">\_\_lshrti3</a>

```cpp
void compiler_builtins.h::__lshrti3 (
    __int128 & res,
    uint64_t lo,
    uint64_t hi,
    uint32_t shift
)
```

Perform logical shift right on a 128 bit integer (which is represented as two 64 bit unsigned integers) 

Perform logical shift right on a 128 bit integer split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **lo** Low 64 bits of the 128 bit factor. 
* **hi** High 64 bits of the 128 bit factor. 
* **shift** Number of bits to shift. 



**Post**

`res` is replaced with the result of the operation Example: 
```cpp
__int128 res = 0;
__int128 a = 8;
__lshrti3(res, a, (a >> 64), 1);
printi128(&res); // Output: 4
```

 




### function <a id="ga2d057451f581f4d1cec929cf76f0d610" href="#ga2d057451f581f4d1cec929cf76f0d610">\_\_ashlti3</a>

```cpp
void compiler_builtins.h::__ashlti3 (
    __int128 & res,
    uint64_t lo,
    uint64_t hi,
    uint32_t shift
)
```

Perform arithmetic shift left on a 128 bit integer (which is represented as two 64 bit unsigned integers) 

Perform arithmetic shift left on a 128 bit integer split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **lo** Low 64 bits of the 128 bit factor. 
* **hi** High 64 bits of the 128 bit factor. 
* **shift** Number of bits to shift. 



**Post**

`res` is replaced with the result of the operation Example: 
```cpp
__int128 res = 0;
__int128 a = 8;
__ashlti3(res, a, (a >> 64), 1);
printi128(&res); // Output: 16
```

 




### function <a id="ga54e1751b41448b01e519dfeb63733ab8" href="#ga54e1751b41448b01e519dfeb63733ab8">\_\_ashrti3</a>

```cpp
void compiler_builtins.h::__ashrti3 (
    __int128 & res,
    uint64_t lo,
    uint64_t hi,
    uint32_t shift
)
```

Perform arithmetic shift right on a 128 bit integer (which is represented as two 64 bit unsigned integers) 

Perform arithmetic shift right on a 128 bit integer split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **lo** Low 64 bits of the 128 bit factor. 
* **hi** High 64 bits of the 128 bit factor. 
* **shift** Number of bits to shift. 



**Post**

`res` is replaced with the result of the operation Example: 
```cpp
__int128 res = 0;
__int128 a = -8;
__ashrti3(res, a, (a >> 64), 1);
printi128(&res); // Output: -4
```

 




### function <a id="ga873d982bbd7493a9975dd88e923d85ed" href="#ga873d982bbd7493a9975dd88e923d85ed">\_\_addtf3</a>

```cpp
void compiler_builtins.h::__addtf3 (
    long double & ret,
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Add two long doubles (which are represented as two 64 bit unsigned integers) 

Add two long doubles split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Post**

`ret` is replaced with the result of the operation 




### function <a id="ga6f055bf1366a170f3f01b28cc0a723dc" href="#ga6f055bf1366a170f3f01b28cc0a723dc">\_\_subtf3</a>

```cpp
void compiler_builtins.h::__subtf3 (
    long double & ret,
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Subtract two long doubles (which are represented as two 64 bit unsigned integers) 

Subtract two long doubles split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Post**

`ret` is replaced with the result of the operation 




### function <a id="ga74a992741c2e037447d9953bb5cce333" href="#ga74a992741c2e037447d9953bb5cce333">\_\_multf3</a>

```cpp
void compiler_builtins.h::__multf3 (
    long double & ret,
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Multiply two long doubles (which are represented as two 64 bit unsigned integers) 

Multiply two long doubles split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Post**

`ret` is replaced with the result of the operation 




### function <a id="gad8133b5d6604ce3bab0adf8e0d44bf5f" href="#gad8133b5d6604ce3bab0adf8e0d44bf5f">\_\_divtf3</a>

```cpp
void compiler_builtins.h::__divtf3 (
    long double & ret,
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Divide two long doubles (which are represented as two 64 bit unsigned integers) 

Divide two long doubles split as two 64 bit unsigned integers and assign the value to the first parameter. 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Post**

`ret` is replaced with the result of the operation 




### function <a id="ga11b0c275233be847ecba192c3d4bd50f" href="#ga11b0c275233be847ecba192c3d4bd50f">\_\_eqtf2</a>

```cpp
int compiler_builtins.h::__eqtf2 (
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Check equality between two doubles (which are represented as two 64 bit unsigned integers) 

Check equality between two doubles split as two 64 bit unsigned integers 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Returns:**

1 if a greater than b 




**Returns:**

0 if a equal to b 




**Returns:**

-1 if a less than b 




**Returns:**

1 if either a or b is NaN 




### function <a id="ga01fedff23a9e5324dab56c77a4ce90fa" href="#ga01fedff23a9e5324dab56c77a4ce90fa">\_\_netf2</a>

```cpp
int compiler_builtins.h::__netf2 (
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Check inequality between two doubles (which are represented as two 64 bit unsigned integers) 

Check inequality between two doubles split as two 64 bit unsigned integers 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Returns:**

1 if a greater than b 




**Returns:**

0 if a equal to b 




**Returns:**

-1 if a less than b  if either a or b is NaN 




### function <a id="gaa4067976976ddf6189ff05068f071421" href="#gaa4067976976ddf6189ff05068f071421">\_\_getf2</a>

```cpp
int compiler_builtins.h::__getf2 (
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Check if the first double is greater or equal to the second double, (the doubles are represented as two 64 bit unsigned integers) 

Check if the first double is greater or equal to the second double, the doubles are split as two 64 bit unsigned integers 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Returns:**

1 if a greater than b 




**Returns:**

0 if a equal to b 




**Returns:**

-1 if a less than b 




**Returns:**

-1 if either a or b is NaN 




### function <a id="ga22ea3ec1bb3c252037a6d1de080f59ec" href="#ga22ea3ec1bb3c252037a6d1de080f59ec">\_\_gttf2</a>

```cpp
int compiler_builtins.h::__gttf2 (
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Check if the first double is greater than the second double, (the doubles are represented as two 64 bit unsigned integers) 

Check if the first double is greater than the second double, the doubles are split as two 64 bit unsigned integers 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Returns:**

1 if a greater than b 




**Returns:**

0 if a equal to b 




**Returns:**

-1 if a less than b 




**Returns:**

0 if either a or b is NaN 




### function <a id="ga1c52620ce5caeab3f24d20848de48020" href="#ga1c52620ce5caeab3f24d20848de48020">\_\_letf2</a>

```cpp
int compiler_builtins.h::__letf2 (
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Check if the first double is less or equal to the second double, (the doubles are represented as two 64 bit unsigned integers) 

Check if the first double is less or equal to the second double, the doubles are split as two 64 bit unsigned integers 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Returns:**

1 if a greater than b 




**Returns:**

0 if a equal to b 




**Returns:**

-1 if a less than b 




**Returns:**

1 if either a or b is NaN 




### function <a id="ga31e5201b17ecf49bf0544d619b3a211e" href="#ga31e5201b17ecf49bf0544d619b3a211e">\_\_lttf2</a>

```cpp
int compiler_builtins.h::__lttf2 (
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Check if the first double is less than the second double, (the doubles are represented as two 64 bit unsigned integers) 

Check if the first double is less than the second double, the doubles are split as two 64 bit unsigned integers 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Returns:**

1 if a greater than b 




**Returns:**

0 if a equal to b 




**Returns:**

-1 if a less than b 




**Returns:**

0 if either a or b is NaN 




### function <a id="ga130b5f6598f3db086bc0767c6be028c0" href="#ga130b5f6598f3db086bc0767c6be028c0">\_\_cmptf2</a>

```cpp
int compiler_builtins.h::__cmptf2 (
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Compare two doubles (the doubles are represented as two 64 bit unsigned integers) 

Compare two doubles which are split as two 64 bit unsigned integers 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Returns:**

1 if a greater than b 




**Returns:**

0 if a equal to b 




**Returns:**

-1 if a less than b 




**Returns:**

1 if either a or b is NaN 




### function <a id="ga26cb1a82545578282008ab4dc67cf262" href="#ga26cb1a82545578282008ab4dc67cf262">\_\_unordtf2</a>

```cpp
int compiler_builtins.h::__unordtf2 (
    uint64_t la,
    uint64_t ha,
    uint64_t lb,
    uint64_t hb
)
```

Check if either of the doubles is NaN, (the doubles are represented as two 64 bit unsigned integers) 

Check if either of the doubles is NaN, the doubles are split as two 64 bit unsigned integers 

**Parameters:**


* **res** It will be replaced with the result product. 
* **la** Low 64 bits of the first 128 bit factor. 
* **ha** High 64 bits of the first 128 bit factor. 
* **lb** Low 64 bits of the second 128 bit factor. 
* **hb** High 64 bits of the second 128 bit factor. 



**Returns:**

1 if either a or b is NaN 




**Returns:**

0 if either a or b is not NaN 




### function <a id="ga3feafc107fc44ac8039a667ee49bcdbf" href="#ga3feafc107fc44ac8039a667ee49bcdbf">\_\_extendsftf2</a>

```cpp
void compiler_builtins.h::__extendsftf2 (
    long double & ret,
    float f
)
```

Extend float to long double. 

Extend float to long double 

**Parameters:**


* **ret** It will be replaced with the result product. 
* **f** Input float to be extended 



**Post**

`ret` is replaced with the extended float 




### function <a id="gae76415cbe79dbac141141a706158552c" href="#gae76415cbe79dbac141141a706158552c">\_\_extenddftf2</a>

```cpp
void compiler_builtins.h::__extenddftf2 (
    long double & ret,
    double f
)
```

Extend float to long double. 

Extend double to long double 

**Parameters:**


* **ret** It will be replaced with the result product. 
* **f** Input float to be extended 



**Post**

`ret` is replaced with the extended float 




### function <a id="gafb30709e77efa4ef9eb3bf4d42004ecf" href="#gafb30709e77efa4ef9eb3bf4d42004ecf">\_\_fixtfdi</a>

```cpp
int64_t compiler_builtins.h::__fixtfdi (
    uint64_t l,
    uint64_t h
)
```

Convert long double (which are split as two 64 bit unsigned integers) into 64 bit integer. 

Convert long double (which are split as two 64 bit unsigned integers) into 64 bit integer 

**Parameters:**


* **l** Low 64 bits of the first 128 bit factor. 
* **h** High 64 bits of the first 128 bit factor. 



**Returns:**

the converted 64 bit integer. 




### function <a id="gac2669376b81a47fc865f5ba54aea0720" href="#gac2669376b81a47fc865f5ba54aea0720">\_\_fixtfsi</a>

```cpp
int32_t compiler_builtins.h::__fixtfsi (
    uint64_t l,
    uint64_t h
)
```

Convert long double (which are split as two 64 bit unsigned integers) into 32 bit integer. 

Convert long double (which are split as two 64 bit unsigned integers) into 32 bit integer 

**Parameters:**


* **l** Low 64 bits of the first 128 bit factor. 
* **h** High 64 bits of the first 128 bit factor. 



**Returns:**

the converted 32 bit integer. 




### function <a id="ga459b47b617b89052f544025349c165f8" href="#ga459b47b617b89052f544025349c165f8">\_\_fixunstfdi</a>

```cpp
uint64_t compiler_builtins.h::__fixunstfdi (
    uint64_t l,
    uint64_t h
)
```

Convert long double (which are split as two 64 bit unsigned integers) into 64 bit unsigned integer. 

Convert long double (which are split as two 64 bit unsigned integers) into 64 bit unsigned integer 

**Parameters:**


* **l** Low 64 bits of the first 128 bit factor. 
* **h** High 64 bits of the first 128 bit factor. 



**Returns:**

the converted 64 bit unsigned integer. 




### function <a id="ga1c62ec774bd084b04118fdb2b019a5c3" href="#ga1c62ec774bd084b04118fdb2b019a5c3">\_\_fixunstfsi</a>

```cpp
uint32_t compiler_builtins.h::__fixunstfsi (
    uint64_t l,
    uint64_t h
)
```

Convert long double (which are split as two 64 bit unsigned integers) into 32 bit unsigned integer. 

Convert long double (which are split as two 64 bit unsigned integers) into 32 bit unsigned integer 

**Parameters:**


* **l** Low 64 bits of the first 128 bit factor. 
* **h** High 64 bits of the first 128 bit factor. 



**Returns:**

the converted 32 bit unsigned integer. 




### function <a id="ga386f6c017043419d3d33f9e96cc4ae4c" href="#ga386f6c017043419d3d33f9e96cc4ae4c">\_\_trunctfdf2</a>

```cpp
double compiler_builtins.h::__trunctfdf2 (
    uint64_t l,
    uint64_t h
)
```

Convert long double (which are split as two 64 bit unsigned integers) into double. 

Truncate long double (which are split as two 64 bit unsigned integers) into double 

**Parameters:**


* **l** Low 64 bits of the first 128 bit factor. 
* **h** High 64 bits of the first 128 bit factor. 



**Returns:**

the converted double 




### function <a id="ga0de0b2a5fe12abf258f7640987807a3a" href="#ga0de0b2a5fe12abf258f7640987807a3a">\_\_trunctfsf2</a>

```cpp
float compiler_builtins.h::__trunctfsf2 (
    uint64_t l,
    uint64_t h
)
```

Convert long double (which are split as two 64 bit unsigned integers) into float. 

Truncate long double (which are split as two 64 bit unsigned integers) into float 

**Parameters:**


* **l** Low 64 bits of the first 128 bit factor. 
* **h** High 64 bits of the first 128 bit factor. 



**Returns:**

the converted float 




### function <a id="ga612b3f8baa213fa0ce573eec10bbad78" href="#ga612b3f8baa213fa0ce573eec10bbad78">\_\_break\_point</a>

```cpp
void compiler_builtins.h::__break_point ()
```





----------------------------------------
The documentation for this class was generated from the following file: `libraries/eosiolib/compiler\_builtins.h`