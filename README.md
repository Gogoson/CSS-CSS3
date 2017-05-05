# CSS
## Record knowledge points of css.
### 1、animation



```
  @keyframes animationName {
     from {
       Properties:Properties value;
     }
     Percentage {
       Properties:Properties value;
     }
     to {
       Properties:Properties value;
     }
  }   
```   
   或者全部写成百分比的形式： 
    
```   
   @keyframes animationName {
      0% {
         Properties:Properties value;
      }
      Percentage {
         Properties:Properties value;
      }
      100% {
         Properties:Properties value;
      }
    }
```
动画名和持续时间必填，因为持续时间默认为0，其他选填。

动画可以自动触发，但transform的动画是需要手动触发的。

%都不能省略。

	 
