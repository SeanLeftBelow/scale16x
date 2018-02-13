## SCALE 16x

Graphics borrowed from: https://github.com/socallinuxexpo/SCALE-Planning/tree/master/branding
Based off this guide: http://andrewsowa.com/blog/2017/3/19/creating-the-benchoff-nickel

```
inkscape basic_scale_penguin.ai --export-plain-svg=troy.svg
inkscape troy.svg --export-png=troy.png
```

Pull file into KiCAD's Bitmap2Componet Converter
1) Solid silk screen for the belly. 
2) Bare copper for the outline and eye.
3) Bare FR4 (plan fiberglass) will be skipped.
4) Solder-mask (Pruple)
5) Darkest color is solder-mask on bare FR4. (Text)


