# Beispiel facsimile

1. Add the facs elem before body

```
      <facsimile xmlns="http://www.music-encoding.org/ns/mei">
         <surface xml:id="surf0">
            <graphic xml:id="graph0" target="6LeichteStuecklein-07.png"/>
            <zone xml:id="zc33ls7" lrx="550" lry="771" type="measure" ulx="174" uly="481"/>
         </surface>
      </facsimile>
```

2. Add pb at right place
```
<pb facs="surf0"/>
```

3. Add facs-id to corresponding element 
```
<measure xml:id="m1sd61ti" facs="#zc33ls7" metcon="false" n="1">
```
