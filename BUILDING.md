### Linux ###

```
git clone https://github.com/tank-trax/ddsp-vst.git
cd ddsp-vst
git checkout linux
bash repo-init.sh
cmake -B buildlin -S . -G "Unix Makefiles" 
cd buildlin
bash release.sh 
make CONFIG=Release -j4 
```
