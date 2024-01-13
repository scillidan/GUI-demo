Just download [releases](https://github.com/torakiki/pdfsam/releases).

## From source (Cache)

```sh
scoop install openjdk21 maven gettext
```	

```sh
git clone https://github.com/torakiki/pdfsam
git checkout v5.2.0
mvn clean install -Drelease
```

Need:

```sh
scoop install gpg
gpg --full-gen-key
```

```sh
gpg --search-keys BF019D784ED7F785
```

Re-run:

```sh
mvn clean install -Drelease
```

## Reference

- [Build-and-run](https://github.com/torakiki/pdfsam/wiki/Build-and-run).
- [理解和使用 GPG](https://www.rectcircle.cn/posts/understand-and-use-gpg/)

## Troubleshoot

- [Can't verify packages, GPG keys return no user ID](https://github.com/torakiki/pdfsam/issues/472)