# AnalogGaugeWidgetPyQt6

Custom QWidget
- Compatible with PyQt6 only
- PyQt 4 & 5 versions can be cloned from the original project https://github.com/StefanHol/AnalogGaugeWidgetPyQt

![AnalogGaugeWidgetDemo Image](img/AnalogGaugeWidgetDemo.JPG?raw=true "AnalogGaugeWidgetDemo")

## Usage:
- Multiple vísualisatins
- Show speed
- fuel indicator
- level indicator
- etc

## Interface

### Update Value Method
update_value(int) -> will also redraw the widget

### Value Changed Signal
valueChanged(int)

## Demo & Parameters Selection

Run the demo from a shell
1. Clone the project to your local workstation
2. Run either in the Windows PowerShell or Max/Linux bash

Windows PowerShell

```bash
cd AnalogGaugeWidgetPyQt
virtualenv venv
venv\Scripts\activate
pip install PyQt6
python analoggaugewidget.py
```

Or Linux/Mac

```bash
cd AnalogGaugeWidgetPyQt
python -m venv venv
source venv/bin/activate
pip install PyQt6
python analoggaugewidget.py
```

![AnalogGaugeWidgetDemo Image](img/Example_without_needle.JPG?raw=true "Add custom widget")
