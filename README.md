# Lab8-Starter

## How are graceful degradation and service workers related?
Service workers contribute to graceful degredation of a webapp. Since service workers can store data from network requests, the service worker can substitute for this network request in future requests. The webapp would not completely fall apart without a network connection because of the service worker, which is the concept of graceful degredation. 