###### The Lithe Project&trade; Development Team

## $LXTH Explorer

Block explorer for $LXTH, a CryptoNote based cryptocurrency.

#### Installation

- It takes data from daemon `lithe-daemon`. 
- It should be accessible from the Internet. 
- Run `lithe-daemon` with open port as follows:

```bash
./lithe-daemon --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=30000
```

2) Upload to your website and change 'api' variable in `config.js` to point to your daemon.

### Development, Copyrights and Notes

- Devs: @aivve @taegus @katz @devopsralf @LithyRiolu
- Copyright: Karbovanets, Conceal Network and The Lithe Project
