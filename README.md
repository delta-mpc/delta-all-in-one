# Delta Network All-in-One Start Script

This repository contains the docker-compose start scripts and
other necessary config files to start a minimum Delta network.

## Minimum Delta Network without Blockchain

![network-structure](./assets/minimum-non-blockchain.png)

The minimum network without Blockchain contains a Chain Connector instance running at coordinator mode, 2 Delta Nodes contains test MNIST data, and a Deltaboard instance.
To start the network, clone this repository in your local environment:

```
$ git clone https://github.com/delta-mpc/delta-all-in-one.git
```

Then use docker-compose to start the network:

```
$ cd delta-all-in-one/no-blockchain
$ docker-compose up -d
```

After downloading the image and starting the container, we can already visit Deltaboard in the browser through:

```
http://localhost:8090
```

## Minimum Delta Network with Blockchain

![network-structure](./assets/minimum-with-blockchain.png)

The minimum network with Blockchain contains a Delta Chain Node, two Chain Connector instances running at Blockchain mode,
2 Delta Nodes contains test MNIST data, and a Deltaboard instance.
To start the network, clone this repository in your local environment:

```
$ git clone https://github.com/delta-mpc/delta-all-in-one.git
```

Then use docker-compose to start the network:

```
$ cd delta-all-in-one/with-blockchain
$ docker-compose up -d
```

After downloading the image and starting the container, we can already visit Deltaboard in the browser through:

```
http://localhost:8090
```
