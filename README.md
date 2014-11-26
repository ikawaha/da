# Double Array Trie

## Usage

```
keywords := []string{
         "電気",                
         "電気通信",              
         "電気通信大学",            
         "電気通信大学院大学",         
         "電気通信大学大学院",         
         "電気通信大学電気通信学部",      
         "電気通信大学大学院電気通信学研究科",
}		
d := &DoubleArray{}
d.Build(keywords)
ids, lens := d.CommonPrefixSearch(strings.NewReader("電気通信大学大学院電気通信学研究科"))
```

## Copyright and license

Copyright (c) 2014 ikawaha Rights Reserved.

This software is released under the MIT License. See LICENSE.txt
