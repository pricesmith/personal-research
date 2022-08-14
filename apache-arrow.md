# Apache Arrow

![image](https://user-images.githubusercontent.com/62907266/184539547-0c0e076c-10a0-49ab-90b0-44229b4bcd5d.png)

![image](https://user-images.githubusercontent.com/62907266/184539563-e5638511-f66f-40ee-a959-c0a8f10f0500.png)

## Standardization Saves
Without a standard columnar data format, every database and language has to implement its own internal data format. This generates a lot of waste. Moving data from one system to another involves costly serialization and deserialization. In addition, common algorithms must often be rewritten for each data format.

Arrow's in-memory columnar data format is an out-of-the-box solution to these problems. Systems that use or support Arrow can transfer data between them at little-to-no cost. Moreover, they don't need to implement custom connectors for every other system. On top of these savings, a standardized memory format facilitates reuse of libraries of algorithms, even across languages.
