## From source

```sh
git clone https://github.com/chaiNNer-org/chaiNNer
cd chaiNNer
npm install
npm run make
unzip out/make/zip/win32/x64/chaiNNer-win32-x64-x.xx.x.zip -d D:/opt/chaiNNer
```

```sh
scoop install python39
python39 -m pip uninstall torch
python39 -m pip cache purge
python39 -m pip install torch -f https://download.pytorch.org/whl/torch_stable.html
```

```sh
cd D:/opt/chaiNNer
echo true > settings/use-system-python
where python // chaiNNer will should use the first.
chaiNNer.exe
```