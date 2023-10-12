# microsoft_office_activate

Open cmd program with administrator rights.
First, you need to open cmd in the admin mode,

# Command Below

cd /d %ProgramFiles(x86)%\Microsoft Office\Office16
OR
cd /d %ProgramFiles%\Microsoft Office\Office16

for /f %x in ('dir /b ..\root\Licenses16\ProPlus2021VL_KMS*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"

cscript ospp.vbs /setprt:1688
cscript ospp.vbs /unpkey:6F7TH >nul
cscript ospp.vbs /inpkey:FXYTK-NJJ8C-GB6DW-3DYQT-6F7TH
cscript ospp.vbs /sethst:e8.us.to
cscript ospp.vbs /act





