# VS2019_Assembly_64Bits
Guide to configure 64 bits Assembly environment in VS2019

## 1.Create "C++ Empty Project"

<img src="/images/Empty_Project.png" width="635" height="124" />

## 2.Open "Test--Options"

<img src="/images/Options.PNG" width="523" height="186.5" />

## 3.Change default "Projects Location"

<img src="/images/Location.png" width="474" height="284.5" />

## 4.Set "Build Customizations...."

<img src="/images/Build.PNG" width="453.5" height="331.5" />

## 5.Enable masm

<img src="/images/masm.PNG" width="294.5" height="185" />

## 6.Configure Propertires

<img src="/images/Properties.PNG" />

## 7.Set Entry Point as "main"

<img src="/images/Advanced.PNG" width="492.5" height="342" />

## 8.Set "x64" Debug

<img src="/images/x64.PNG" />

Tips: If you use *Template* to new a 64bits Assembly Language Project, Debugger usually is *x86* rather than *x64*, Please adjust it to *x64* to avoid errors.

## 9.Add "Source.asm"

<img src="/images/Add_asm.PNG" />

## 10.Code Template

<img src="/images/Code_Template.PNG" />

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

## 11.Add *Existing Item*

<img src="/images/addExistingItem.PNG" width="442" height="313" />

## 12.Add *Irvine64* Library

<img src="/images/irvine64.PNG" width="428" height="270" />


## 13.*LARGEADDRESSAWARE* Error

<img src="/images/error.PNG" width="435" height="53.5" />

## 14.Open properties

<img src="/images/projectProperties.PNG" width="454" height="586" />

## 15.set *Enable Large Addresses* to *NO*

<img src="/images/eLA_NO.PNG" width="491.5" height="322" />
