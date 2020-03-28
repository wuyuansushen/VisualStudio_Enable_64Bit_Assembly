# VS2019_Assembly_64Bits
Guide to configure 64 bits Assembly environment in VS2019

## 1.Create "C++ Empty Project"

<img src="Empty_Project.png" width="635" height="124" />

## 2.Open "Test--Options"

<img src="Options.PNG" width="523" height="186.5" />

## 3.Change default "Projects Location"

<img src="Location.png" width="474" height="284.5" />

## 4.Set "Build Customizations...."

<img src="Build.PNG" width="343" height="357.5" />

## 5.Enable masm

<img src="masm.PNG" width="294.5" height="185" />

## 6.Configure Propertires

<img src="Properties.PNG" />

## 7.Set Entry Point as "main"

<img src="Advanced.PNG" width="492.5" height="342" />

## 8.Set "x64" Debug

<img src="x64.PNG" />

## 9.Add "Source.asm"

<img src="Add_asm.PNG" />

## 10.Code Template

<img src="Code_Template.PNG" />

```
ExitProcess proto

.data

.code
main proc
	
	mov rcx,0
	call  ExitProcess
main endp
end
```
