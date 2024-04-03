### ENTRY POINT

ENTRY POINT is also used to run the container just like "CMD". But there are few differences.
1. We can't override "ENTRYPOINT", but can override "CMD"
2. We can't override "ENTRYPOINT", if you try to do so it will go and append to the ENTRYPOINT command.