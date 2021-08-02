# C2X-Client-Py

[![Tool Category](https://badgen.net/badge/Tool/C2%20Client/black)](https://github.com/nxenon/c2x-client-py)
[![APP Version](https://badgen.net/badge/Version/Beta/red)](https://github.com/nxenon/c2x-client-py)
[![Python Version](https://badgen.net/badge/Python/3.X/blue)](https://www.python.org/download/releases/3.0/)
[![License](https://badgen.net/badge/License/GPLv2/purple)](https://github.com/nxenon/c2x-client-py/blob/master/LICENSE)

C2X-Client-Py is client of [C2X](https://github.com/nxenon/c2x) (C2/Post Exploitation) project in Python language.

Run
----
    First you should put server IP and server remote port on source code:
    in lines 212 & 213
    then run the code:
    python3 c2x-client.py


- If you have replaced the ip and port in source code you can run the code without any argument.
    - python3 c2x-client.py
- If you didn't replace the ip and port, or you want to connect to different server or port you can use arguments.
    - python3 c2x-client.py --ip 127.0.0.1 --port 54321
    
- Optional Arguments
    - --ip Remote_IP
    - --port Remote_Port

Help
----
    
    usage: c2x-client.py [-h] [--ip IP] [--port PORT]
    
    optional arguments:
      -h, --help   show this help message and exit
      --ip IP      Server Remote IP [Default : replace_server_ip]
      --port PORT  Server Remote Port [Default : replace_server_port]
