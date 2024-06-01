# FWPM_ENGINE_COLLECT_NET_EVENTS

Disable Net Events is Designed to disable FWPM_ENGINE_COLLECT_NET_EVENTS which is enabled default in windows filtering platform

Get Net Event Value is Designed to read current value from FWPM_ENGINE_COLLECT_NET_EVENTS
Value 1 = enabled
Value 0 = disabled


Open Visual Studio.
Create a new project or open an existing one. For this example, create a new Console Application project in C++.


Link Against the Library:

Right-click your project in the Solution Explorer and select "Properties".
Go to Configuration Properties -> Linker -> Input.
In the "Additional Dependencies" field, add Fwpuclnt.lib. Ensure it looks something like this: Fwpuclnt.lib;%(AdditionalDependencies).

Then Hit run in Visual studio and a command prompt will open with succed/error in Disable net Events 
Get Net event Value prints current value in the console
