---
title: KD-Tree
date: '2019-05-07T15:07:03.284Z'
subtitle:
---

<h2>With KD-Tree</h2>

![gourd-kd](./kd_data/complex-KD.png)
Objects in KDTree: 648

KDTree constructed in: 00:00:00.0616881

Rendered single 1000x1000 image in: 10.664 Seconds

![balls-kd](./kd_data/balls-kd.png)
Objects in KDTree: 4001

KDTree constructed in: 00:00:00.2151792

(shorter construction time due to easier sphere-AABB intersection tests)

Rendered single 1000x1000 image in: 1 Minute, 59.569 Seconds

<h2>WithOUT KD-Tree</h2>

![balls-kd](./kd_data/balls-nokd.png)
Rendered single 1000x1000 image in: 14 Minutes, 26.977 Seconds

![gourd-kd](./kd_data/complex-no-KD.png)

Rendered single 1000x1000 image in: 42.987 Seconds
