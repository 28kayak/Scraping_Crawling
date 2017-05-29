- the command below will download a png file in the current direcotry. 
```sh
wget http://image.gihyo.co.jp/assets/templates/gihyojp2007/image/gihyo_logo.png
```

- the command below will download a `index.html` in the current directry.
```sh
wget http://gihyo.jp/
```
- the following commnad allow to create gihyo.jp dir and download inside of gihyo.jp.
```sh
wget -r --no-parent -w 1 -l 1 --restrict-file-names=nocontrol https://gihyo.jp/dp/

```
OPTIONS
`-w time` set waiting between download. 
`-l depth` set depth of file directry to be downloaded 
`-r` recursivly download