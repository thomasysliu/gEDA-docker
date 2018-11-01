# gEDA-docker
gEDA pcb design docker file

#Usage


$ docker run -ti --rm --network=host -e DISPLAY=$DISPLAY -v $HOME/.Xauthority:/home/developer/.Xauthority:ro -u root thomasysliu/geda-docker bash


$ docker run -ti --rm --network=host -e DISPLAY=$DISPLAY -v $HOME/.Xauthority:/home/developer/.Xauthority:ro -u root thomasysliu/geda-docker pcb


$ docker run -ti --rm --network=host -e DISPLAY=$DISPLAY -v $HOME/.Xauthority:/home/developer/.Xauthority:ro -u root thomasysliu/geda-docker gschem


$ docker run -ti --rm --network=host -e DISPLAY=$DISPLAY -v $HOME/.Xauthority:/home/developer/.Xauthority:ro -u root thomasysliu/geda-docker gerberv
