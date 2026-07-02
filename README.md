1. css Box Model
Har element ek box hota hai
+---------------------+
|       Margin        |
|  +---------------+  |
|  |    Border     |  |
|  | +-----------+ |  |
|  | | Padding   | |  |
|  | | +-------+ | |  |
|  | | |Content| | |  |
|  | | +-------+ | |  |
|  | +-----------+ |  |
|  +---------------+  |
+---------------------|
* Parts
Content → Actual text/image
Padding → Content ke andar ki space
Border → Box ki boundary
Margin → Bahar ki space
Example:
div{
  width:200px;
  padding:20px;
  border:5px solid black;
  margin:10px;
}
