# TransformationFadeView

> Animation With MaskView

![normal图片](/demo.gif) 

## How to use

* Import "TransformationFadeView.h"
* Use like this

```
    self.tranformFadeViewTwo                 = [[TranformFadeView alloc] initWithFrame:self.view.bounds];
    self.tranformFadeViewTwo.contentMode     = UIViewContentModeScaleAspectFill;
    self.tranformFadeViewTwo.image           = [UIImage imageNamed:@"2"];
    self.tranformFadeViewTwo.verticalCount   = 5;
    self.tranformFadeViewTwo.horizontalCount = 5;
    self.tranformFadeViewTwo.center          = self.view.center;
    [self.tranformFadeViewTwo buildMaskView];
    
    self.tranformFadeViewTwo.fadeDuradtion        = 1.f;
    self.tranformFadeViewTwo.animationGapDuration = 0.1f;
    
    [self.view addSubview:self.tranformFadeViewTwo];
    [self.tranformFadeViewTwo fadeAnimated:YES];

```

Enjoy it :)
