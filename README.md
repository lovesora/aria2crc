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

# or
# if you installed lx-rc
rc aria2 --install
```

## Step 2. Copy .aira2rc to `~/.aria2rc`
```bash
# cd aria2rc directory
cp .aria2rc ~/.aria2rc

# or
rc aria2 --install
```

## Step 3. Start aria2
```bash
# change --conf-path value to your .aria2rc path
# notice that the path should be absolute path, not ~/.aria2rc
aria2c --conf-path=/Users/liuxin/.aria2rc

# or
rc aria2 --start
```

## Finally. Open http://lovesora.github.io/yaaw-aria2
Enjoy the download speed!

