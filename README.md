# Standalone Printrbot v2 Gcode Converter

This python script allows you to convert Simplify3d gcode for Printrbot v2, just delete Start & End .gcode in your profiles and use as described.

If you use Cura is better to add Cura plugin from [Printrbot Repository](https://github.com/Printrbot/cura-simple2016-plugin)

##Usage

```$python simple_converter.py --eto [eto] --fanOutput [fanOutput] --fanMinInValue [fanMinInValue] --fanMaxOutValue [fanMaxOutValue] --minTraverseSpeed [minTraverseSpeed] --file [file.gco] ```

###Easy way:
If you gone a use default parameters just do:

```$python simple_converter.py --file [file.gco] ```
