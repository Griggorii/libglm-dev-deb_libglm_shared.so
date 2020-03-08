# libglm-dev-deb_libglm_shared.so
libglm-dev , deb , mat2x2 , opencv

$$ sudo apt install cmake-qt-gui -y

Изменить все пути на свои в этом поможет редактирование фаила CMakeCache.txt внутри 
заменить все линки типа /home/griggorii/glm-master на свои в есть такая функция в блокноте 
выделяешь строку вверху находишь заменить и рисует выделенный путь и соответственно меняем все
во всем документе на свой путь после выполняем cmake-qt-gui и указываем папку с проектом за одно удаляем старый makefile

$$ cmake-gui

Жмем generate это создаст новый makefile фаил который вы удалили мо этого

$$ make -j16

$$ sudo make install
