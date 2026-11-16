# Лабораторна робота №1: Вступ до ROS 2
**Виконав:** студент групи КВ-32 Доній Олександр

## Запуск середовища:
1. Збірка образу: `docker build -t ros2_lab1_image .`
2. Запуск контейнера: `docker run -it --rm -v $(pwd)/ros2_ws:/ros2_ws ros2_lab1_image`
3. Збірка коду: `colcon build --symlink-install`
