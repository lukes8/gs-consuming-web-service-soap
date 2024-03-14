### Some useful notes, steps

- it is expected the server producer soap is running (to get wdsl data)
- consumer needs to have access to producer SOAP service to get xml data from wdsl
- wdsl is what describes request and response data what we want as consumers
- hence we need firstly generate classes Request** and Response** based on wdsl url request and then it is copied into generated folder 
- now we may use it via CountryClient etc.

