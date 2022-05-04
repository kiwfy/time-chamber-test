# Time Chamber Test

![alt text](https://github.com/kiwfy/ala-microservice/blob/master/time_chamber.png)

The Hyperbolic Time Chamber (精神と時の部屋 Seishin to Toki no Heya, literal meaning "Spirit and Time Room") is a location that can be accessed through different doorways throughout Universe 7.

When using the entryway to the Hyperbolic Time Chamber through The Lookout on Earth, one year inside the chamber is the equivalent to one day on the outside. A step over the threshold of the training area brings one immediately into ten times Earth's gravity (the same as that of Planet Vegeta, Planet Zoon, and King Kai's Planet). The air thickness is about a quarter of Earth's and the temperature fluctuates the deeper one goes into the training area. 

Besides that is possible to practice and write codes in PHP.

### Install

1. First you need to building a correct environment to install dependences
```sh
docker build -t desafio/desafio-test .
```

2. Access the container
```sh
docker run -v ${PWD}/:/var/www/html -it desafio/desafio-test bash
```

3. Verify if all dependencies is installed (if need anyelse)
```sh
composer install
```

### Validation

Run all the unit test with this command (inside container)
```sh
composer run test
```