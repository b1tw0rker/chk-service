# chk-service

add : /opt/chk-service/bw-chk-service.sh dev to your local .bashrc

know issues: may cuase problems with rsync
Solution: Add
if [ -n "$PS1" ]; then
    echo "Willkommen auf dem Server!"
fi
to your .bashrc scripts.