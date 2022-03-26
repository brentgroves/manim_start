# manim_start
docker run -it --name manim-test -v "/home/brent/srcconda/manim_start:/manim" manimcommunity/manim /bin/bash
docker exec -it manim-test manim -qm test_scenes.py CircleToSquare
