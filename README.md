# aria2crc
aria2c configuration

# Usage
## Step 1. Installation
```bash
git clone https://github.com/aria2/aria2.git
cd aria2
./configure
make
make install
```

## Step 2. Copy .aira2rc to `~/.aria2rc`
```bash
# cd aria2rc directory
cp .aria2rc ~/.aria2rc
```

## Step 3. Start aria2
```bash
# change --conf-path value to your .aria2rc path
# notice that the path should be absolute path, not ~/.aria2rc
aria2c --conf-path=/Users/liuxin/.aria2rc
```

## Finally. Open http://lovesora.github.io/aria2-web
Enjoy the download speed!

