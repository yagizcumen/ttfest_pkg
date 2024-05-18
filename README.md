
## Kurulum
```bash
  cd ~/ros2_ws/src
  git clone https://github.com/Albaryan/ttfest_pkg.git
  cd ~/ros2_ws
  colcon build --symlink-install
```

## Gazebo'da simülasyonu açmak için
```bash
  ros2 launch ttfest_pkg ttfest_launch.py
```

## Kameradan gelen veriyi görmek için
```bash
   ros2 run ttfest_pkg camera_node.py
```

## Araç hareketini test etmek için
```bash
   ros2 run ttfest_pkg control_node.py
```

## LIDAR'ı test etmek için
```bash
   ros2 run ttfest_pkg lidar_node.py
```

## Şerit takibini çalıştırmak için
```bash
   ros2 run ttfest_pkg lane_following_node.py
```
