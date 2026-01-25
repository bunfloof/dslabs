### lab0

_JAVA_OPTIONS='-Dsun.java2d.xrender=false' ./run-tests.py --lab 0 --debug 1 1 "Hello World"
_JAVA_OPTIONS='-Dsun.java2d.opengl=false -Dsun.java2d.xrender=false' ./run-tests.py --lab 0 --debug 1 1 "Hello World"

Force software rendering (works):
```bash
_JAVA_OPTIONS='-Dsun.java2d.pmoffscreen=false' ./run-tests.py --lab 0 --debug 1 1 "Hello World"
```

```
echo "export _JAVA_OPTIONS='-Dsun.java2d.xrender=false'" >> ~/.bashrc
source ~/.bashrc
```
