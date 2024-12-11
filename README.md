# Xbox Controller Macro Helper

A command-line tool that allows you to create macros for Xbox controllers. It detects your controller, lets you select a button to macro, and simulates the button press at a custom interval while the button is held down.

## Features
- Detects Xbox controllers (USB/Bluetooth).
- Select and macro any button.
- Customize the macro speed (in ms).
- Hold the button to start the macro, release to stop.
- Logs actions to the console.

 ## Requirements
- **Windows** OS.
- .NET Core 6.0+.
- [SharpDX.XInput](https://github.com/sharpdx/SharpDX) for Xbox controller support.
- Xbox controller connected via USB or Bluetooth.

## How to Use

### 1. Clone or Download
Clone or download the repository.

```bash
git clone https://github.com/yourusername/XboxControllerMacro.git
```

### 2. Install SharpDX
Install SharpDX via NuGet:

```bash
Install-Package SharpDX.XInput
```

### 3. Build and Run
Build and run the application:

```bash
dotnet run
```

### 4. Select and Macro a Button
- Press a button to macro.
- Confirm the button choice and set the macro speed (in ms).
- Hold the button to start the macro; release to stop.

## Example:
```bash
This is a open source free use project.

Discord = fenix.wow

Starting Controller Macro...

Controller found!

Press the button you would like to macro.
Button pressed: LeftThumb
Is this what you would like to macro? Y/N
Y
How fast would you like this button to be macro'd? (In ms)
100
Done! Press and hold this button to start the macro. Release to stop.
Macro started.
Macro action performed.
Macro ended and pressed 1 times.
```

### 5. Exit
Close the console or press `Ctrl + C` to exit.

# License
MIT License
