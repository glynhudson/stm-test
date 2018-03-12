## Upload to STM NUCLEO

### Using PlatformIO

Install platformIO core: https://platformio.org/. It's also possible to use PlatformIO IDE based on Atmom. I prefer using the core CLI .

See out platformio user guide: https://guide.openenergymonitor.org/technical/compiling/

### Compile and Upload 

```
git clone https://github.com/glynhudson/stm-test
cd smt-test/blinky
pio run -t upload
```
