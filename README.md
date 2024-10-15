# Папочка (Foldy)

## Описание

Менеджер папок для мобильных устройств

## Установка

### ALT Linux (Sisyphus)

#### APT-REPO

```sh
su -
apt-repo test 355276
```

#### EPM

```sh
epmi task
```

> [!WARNING]
> Для использования необходим `sudo`
>
> ```sh
> su -
> apt-get install sudo
> control sudowheel enabled
> ```

### Из исходников

```sh
su -
apt-get update
apt-get install git meson
exit
git clone https://github.com/alt-gnome/Foldy
cd Foldy
meson setup build
cd build
meson compile
```
