# CSS Positioning-playlist log

### Day 13: September 10, 2017    

**Today's Progress**:   
1. Today I learnt about Floating Columns.  
2. Text columns.  
3. Postion Relative.  
4. Fixed Position.  
 

**Thoughts**:     
1. `float: left; width: 46%;` to divide it in two columns.  
2. `column-count, column-gap, column-rule` to separate the columns.  
3. When `position:relative` is set, you can offset the elements witht `left, right, top, bottom`.  I will keep the element in normal document flow
4. `position:absolute` will remove an element from the normal document flow. It's position will be absolute compare to its closest relative parent element. 
5.`position:fixed` Always is relative to the document window. Will remove an element from the normal document flow. 

### Day 12: September 9, 2017    

**Today's Progress**:   
1. Today I learnt about CSS Positioning.  
2. Normal document flow.   
3. Floating elements.  
4. Clearing Floats.  
 

**Thoughts**:     
1. `display:inline-block` makes the inline elements like `a or span` to behave like blocks elements like `p or div`.  
2.  `line-height` defines the height of the line in a text, the space between lines.  
3. The `float` property is makes an element to break the normal document flow. No longer occupy a hight.  
4. The `margin`, `padding` should be taken cared when we use the `width` and `height`.  
5.  The `clear`  property restore the normal document flow. It has to be placed at the end of the element.   
6. Take a look at the `:after{content:"";display:block; clear:both}` rule.  
