* Sur l'instance redis-0 :
  ```
  redis-cli
  -> auth azerty
  -> set stage kube
  -> get stage
  ```

* Sur une autre instance :
  ```
  redis-cli
  -> auth azerty
  -> get stage
  ```
