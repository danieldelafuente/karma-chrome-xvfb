# karma-chrome-xvfb

Docker image including karma, Google Chrome and Xvfb.

The default command of the image is `karma start --single-run`. You can run it by just mapping your karma project into the `app` folder and launch it.

```sh
docker run --rm -v /your/project/dir:/app jramcast/karma-chrome-xvfb
```
