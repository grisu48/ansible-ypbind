# ansible-ypbind

This is an ansible role for installing the NIS client

This is a very simple role and barely works on my systems. It probably will not work for you.
Assume it's gonna explode and cases unpredictable harm :-)

## Role Variables

This 

    yp_nisdomain :  Domain name
    yp_nisserver :  NIS server (Host or IP)

## Example Playbook  

Here is a an example playbook, that should work just as it comes

    ---
    
    - hosts: all
      vars:
        yp_nisdomain: domain.local
        yp_nisserver: server.local
      roles:
         - ansible-ypbind


## License  

This work is [MIT](LICENSE) licensed.

## Author Information  

[F. Niederwanger](https://github.com/grisu48)
