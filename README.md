# hi

cryptochat experiments

## plan

- merkle signing of chat messsages
- fixed length messages like twitter - no images
- partitioning by user names or user tokens to avoid huge chains
- tor client built in?
- for journalism
- gzip or stream compress old blocks and take new hash?
- reply chains can go to the same partition as parent msg?
- allow forks to occur for simultaneous messages but must be rectified in some deterministic manner?
- popular consensus vs blockchain consensus? ...

## pitfalls

- how to keep proof of work from being monopolized?
- usernames - like namecoin? or like proof of stake? ...
- 

## solutions

- ASIC-Resistant or Memory-Hard Algorithms
  - Use algorithms like Equihash (used in Zcash) or RandomX (used in Monero), which are more challenging for ASICs or CPUs to dominate due to their memory and computational intensity.
  - Memory-hard algorithms can help level the playing field, as high memory requirements limit the advantage of custom hardware.
- label the algorithm used. enforce change after X messages?
