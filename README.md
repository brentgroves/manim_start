# manim_start
# to make changes in container
docker run -it --name manim-test -v "/home/brent/srcconda/manim_start:/manim" manimcommunity/manim /bin/bash
# to start container
docker start manim-test
# to render CircleToSquare 
docker exec -it manim-test manim -qm scene.py CircleToSquare
