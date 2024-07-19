--print all methods of connected peripheral. 
--You must be able to connect a modem to the desired block. 
--Rightclicking the modem while it is connected to the network prints in the chat the string of the peripheral. 
-- Creates the file "output.txt" and all available methods as one long string.

function printMethods()
local file = fs.open("output.txt", "w")
for i,v in ipairs(peripheral.getMethods("Example"))
do file.write(i..". "..v)
file.close()
end
