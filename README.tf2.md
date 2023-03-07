* https://qiita.com/poteto0/items/25ce59b08af390e8514b

```
$ tf_upgrade_v2 --intree ./ --outtree ./ --reportfile report.txt
$ tf_upgrade_v2 --intree ./lib/ --outtree ./lib/ --reportfile report_lib.txt
$ pip install tf_slim tensorflow-addons 
```

```
import tf_slim as slim
import tensorflow_addons as tfa
tf.compat.v1.disable_eager_execution()
pre_warp_hi = tfa.image.dense_image_warp(pre_gen, gen_flow)
```
