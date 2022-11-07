# GISNav ROS 2 Message Definitions

This ROS 2 package contains definitions for messages used by the [GISNav package](https://github.com/hmakelin/gisnav).

# Install

```bash
cd colcon_ws
git clone https://github.com/hmakelin/gisnav_msgs.git src/gisnav_msgs
colcon build --packages-select gisnav_msgs
```

# Use Example (Python)

```python
from gisnav_msgs.msg import OrthoImage3D

msg = OrthoImage3D()
msg.bbox = ...
```

# License

This software is released under the MIT license. See the `LICENSE.md` file for more information.
