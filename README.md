# Docker Image for Elixir Exercism

We want to improve the user experience for all Exercism users. We want to make it as easy as possible to get up and running solving exercises without the frustration. Windows users usually run into some sort of installation problems too.

One way we can achieve this is by setting up environments ourselves for them to use via Docker! So in the Elixir track, we can provide participants a Docker image to use. Sometimes users also don't want to install too many packages in their machine to avoid cluttering.

Users would just need to type in something like:

```bash
$ docker run -it -v $(pwd):/root/exercism/elixir exercism-elixir
```

And get started asap!
