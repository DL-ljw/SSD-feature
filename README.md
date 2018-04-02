# SSD-feature
this is the code of our ICPR2028 paper"Feature reusing and semantic aggregation for single stage object detctor".
This idea is very easy to implement.
It is extremly easy to re-produce.
You just need to replace the ssd_pascal.py( https://github.com/weiliu89/caffe/tree/ssd) with ours.
Our ssd_pascal.py is similar to the original except the function AddExtraLayers
and mbox_source_layers = ['eltwisesum5', 'eltwisesum4', 'eltwisesum3', 'eltwisesum2', 'eltwisesum1', 'conv9_22'].
Any problem please contact us. email:lgm_jw@163.com or wechat 18663816743.
It achieves the 79% mAP, train on 07+12 trainval and test on 2007.
For now the best result of SSD-series(DSSD,StairNet and so on).

